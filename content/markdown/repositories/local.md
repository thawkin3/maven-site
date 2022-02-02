# Maven Local Repositories

<!--
Licensed to the Apache Software Foundation (ASF) under one
or more contributor license agreements.  See the NOTICE file
distributed with this work for additional information
regarding copyright ownership.  The ASF licenses this file
to you under the Apache License, Version 2.0 (the
"License"); you may not use this file except in compliance
with the License.  You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing,
software distributed under the License is distributed on an
"AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
KIND, either express or implied.  See the License for the
specific language governing permissions and limitations
under the License.
-->

The local repository is mixed bag, in sense, that it serves two purposes: it caches downloaded artifacts from
remote repositories along with locally built and installed ones.

As noted on [Layout](layout.md) page, locally built and installed artifacts with use baseVersion while calculating
layout. Snapshots pulled from remote will use version property instead, hence they will have the full-blown
"timestamped" version format applied.