# Usage

- Add LitmusChaos to the spinnaker plugin list by modifying the halyard config as provided below. Refer: [plugin-v2-configuration](https://spinnaker.io/guides/user/plugins/#plugin-v2-configuration-changes)

```
  spinnaker:
    extensibility:
      plugins:
        Litmuschaos.PreconfiguredJobPlugin:
          id: Litmuschaos.PreconfiguredJobPlugin
          enabled: true
          version: 0.0.3
          extensions: {}
      repositories:
        spinnaker-plugins-repository:
          id: spinnaker-plugins-repository
          url: https://raw.githubusercontent.com/mayadata-io/spinnaker-plugins-repository/main/plugins.json
```

For more details about the plugin visit the [LitmusChaos Plugin Source Repository](https://github.com/mayadata-io/spinnaker-preconfigured-job-plugin)
