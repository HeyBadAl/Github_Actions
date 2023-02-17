# What is Github Actions?

> _Github Actions_ are packaged scripts to automate tasks in a software development workflow in Github.
> You can configure Github Actions to trigger complex workflow that meet yout orgaization's needs; each time developers check new source code into a specific branch, at timed intervals, or manually.
> The result is a reliable and sustainable automated workflow, which leads to a significant decrease in development time.

## Types of Github Actions

- **Container Actions**: the environment is part of the action's code. These actions can only be run in a Linux environment that Github hosts. Constainer actions support many different languages.
- **JavaScript Actions**: don't include the environment in the code. You'll have to specify the environment to execute these actions. You can run these actions in a VM in the cloud or on-premises. JavaScript actions support Linux, MacOS, and Windoes environment.
- **Composite Actions**: allows you to combine multiple workfloe steps within ine action. _Example:_ you can use this feature to bundle together multiple run commands into an action, and then have a workflow that executes the bundled commands as a single step using that action.
