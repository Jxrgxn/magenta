# Copyright 2016 Google Inc. All Rights Reserved.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#    http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

# Description:
# Code shared by models.

package(
    default_visibility = ["//magenta/models:__subpackages__"],
)

licenses(["notice"])  # Apache 2.0

py_binary(
    name = "melody_rnn_create_dataset",
    srcs = ["melody_rnn_create_dataset.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//magenta/lib:sequence_to_melodies",
        # tensorflow dep
    ],
)

py_binary(
    name = "melody_rnn_generate",
    srcs = ["melody_rnn_generate.py"],
    srcs_version = "PY2AND3",
    deps = [
        "//magenta/lib:melodies_lib",
        "//magenta/lib:midi_io",
        # tensorflow dep
    ],
)

py_binary(
    name = "melody_rnn_train",
    srcs = ["melody_rnn_train.py"],
    srcs_version = "PY2AND3",
    deps = [
        # tensorflow dep
    ],
)

