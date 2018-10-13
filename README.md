# spinnaker-template-example
Spinnaker templates to create the pipelines for bake/deploy in public cloud like AWS

#Pre-requisite
- Install and configure the Spinnaker (https://www.spinnaker.io/setup/install/)
- Install the roer (https://github.com/spinnaker/roer)

Steps to create the Pipeline
- Clone this repository (https://github.com/amiteshchandra/spinnaker-template-example)
- Got to templates/ folder
- Update values for following in keys in template
  - account: <account configured in spinnaker>
  - iamRole: base_iam_role (Update the role name instance need to have. Use role which has minimum access for initial test)
  - keyPair: mykey (this is the key name using which you can login to instance created by spinnaker)
