# Licensed to the Apache Software Foundation (ASF) under one
# or more contributor license agreements.  See the NOTICE file
# distributed with this work for additional information
# regarding copyright ownership.  The ASF licenses this file
# to you under the Apache License, Version 2.0 (the
# "License"); you may not use this file except in compliance
# with the License.  You may obtain a copy of the License at
#
#   http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing,
# software distributed under the License is distributed on an
# "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
# KIND, either express or implied.  See the License for the
# specific language governing permissions and limitations
# under the License.

name: 🚀 Feature Request
description: I have a suggestion (and may want to implement it 🙂)!
title: "[Feature] <title>"
labels: ["new feature"]
body:
- type: textarea
  attributes:
  label: Feature Request
  description: >
  Tip: Have you checked the docs, GitHub issues whether someone else has already reported your issue? Maybe the feature already exists?
  placeholder: >
  A concise description of what you're experiencing.
  validations:
  required: false
- type: textarea
  attributes:
  label: Is your feature request related to a problem? Please describe
  description: A clear and concise description of what the problem is. Ex. I have an issue when [...]
  validations:
  required: false
- type: textarea
  attributes:
  label: Describe the solution you'd like
  description: A clear and concise description of what you want to happen. Add any considered drawbacks.
  validations:
  required: false
- type: textarea
  attributes:
  label: Describe alternatives you've considered
  description: A clear and concise description of any alternative solutions or features you've considered.
  validations:
  required: false
- type: textarea
  attributes:
  label: Additional context
  validations:
  required: false
- type: markdown
  value: "Please read the [Contribution Guideline](https://github.com/a2ap/a2a4j/blob/main/CONTRIBUTING.md) before submitting the PR"
