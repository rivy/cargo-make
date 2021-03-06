
* [Overview](#overview)
* [Installation](#installation)
* [Tutorial](#tutorial)
    * [Introduction and Basics](https://medium.com/@sagiegurari/automating-your-rust-workflows-with-cargo-make-part-1-of-5-introduction-and-basics-b19ced7e7057)
    * [Extending Tasks, Platform Overrides and Aliases](https://medium.com/@sagiegurari/automating-your-rust-workflows-with-cargo-make-part-2-of-5-extending-tasks-platform-overrides-1527386dcf87)
    * [Environment Variables, Conditions, Sub Tasks and Mixing](https://medium.com/@sagiegurari/automating-your-rust-workflows-with-cargo-make-part-3-of-5-environment-variables-conditions-3c740a837a01)
    * [Workspace Support, Init/End Tasks and Makefiles](https://medium.com/@sagiegurari/automating-your-rust-workflows-with-cargo-make-part-4-of-5-workspace-support-init-end-tasks-c3e738699421)
    * [Predefined Tasks, CI Support and Conventions](https://medium.com/@sagiegurari/automating-your-rust-workflows-with-cargo-make-part-5-final-predefined-tasks-ci-support-and-4594812e57da)
* [Usage](#usage)
    * [Simple Example](#usage-simple)
    * [Tasks, Dependencies and Aliases](#usage-task-dependencies-alias)
    * [Commands, Scripts and Sub Tasks](#usage-task-command-script-task)
        * [Sub Task](#usage-task-command-script-task-examplesubtask)
        * [Command](#usage-task-command-script-task-examplecommand)
        * [Script](#usage-task-command-script-task-examplescript)
        * [Rust Code](#usage-task-command-script-task-examplerust)
        * [Cross Platform Shell](#usage-task-command-script-task-exampleshell2batch)
        * [Other Programming Languages](#usage-task-command-script-task-examplegeneric)
    * [Default Tasks and Extending](#usage-default-tasks)
        * [Automatically Extend Workspace Makefile](#usage-workspace-extend)
        * [Load Scripts](#usage-load-scripts)
    * [Ignoring Errors](#usage-ignoring-errors)
    * [Platform Override](#usage-platform-override)
    * [Private Tasks](#usage-private-tasks)
    * [Environment Variables](#usage-env)
        * [Global Configuration](#usage-env-config)
        * [Task](#usage-env-task)
        * [Command Line](#usage-env-cli)
        * [Env File](#usage-env-file)
        * [Global](#usage-env-global)
    * [Conditions](#usage-conditions)
        * [Criteria](#usage-conditions-structure)
        * [Scripts](#usage-conditions-script)
        * [Combining Conditions and Sub Tasks](#usage-conditions-and-subtasks)
    * [Continuous Integration](#usage-ci)
        * [Travis](#usage-ci-travis)
        * [AppVeyor](#usage-ci-appveyor)
        * [GitLab](#usage-ci-gitlab)
    * [Predefined Flows](#usage-predefined-flows)
        * [Coverage](#usage-predefined-flows-coverage)
        * [Cargo Commands and Plugins](#usage-predefined-flows-cargo)
        * [Git Commands](#usage-predefined-flows-git)
        * [Flows/Other](#usage-predefined-flows-flows)
        * [Disabling Predefined Tasks/Flows](#usage-predefined-flows-disable)
    * [Workspace Support](#usage-workspace-support)
        * [Skipping Specific Members](#usage-workspace-support-skip-members)
    * [Init and End tasks](#usage-init-end-tasks)
    * [Catching Errors](#usage-catching-errors)
    * [Cli Options](#usage-cli)
    * [Global Configuration](#cargo-make-global-config)
* [Makefile Definition](#descriptor-definition)
* [Task Naming Conventions](#task-name-conventions)
* [Badge](#badge)
* [Roadmap](#roadmap)
* [Contributing](https://github.com/sagiegurari/cargo-make/blob/master/.github/CONTRIBUTING.md)
* [Release History](https://github.com/sagiegurari/cargo-make/blob/master/CHANGELOG.md)
* [License](#license)
