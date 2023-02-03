# Python Plugin AWS EC2 Plugin

**BE CAREFUL WITH AWS CREDENTIALS**

This is a simple plugin that allows you to input your EC2 instance ID, the power action you want to do, and your AWS creds, to control the EC2 instance.

The valid actions are:
- stop
- force_stop
- start
- reboot
- terminate

Examples are in the `input` folder.

### Unit Tests

After installing the poetry dependencies, run all unit tests via:
```bash
# Run all unit tests
python -m unittest tests.test_ec2_plugin
```

### Image Building

You can change this plugin's image version tag in
`.github/workflows/carpenter.yaml` by editing the
`IMAGE_TAG` variable, and pushing that change to the
branch designated in that workflow.
