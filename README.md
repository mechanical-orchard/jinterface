This repo distributes Erlang/OTP's jinterface package as a maven package published to an attach github package repository.

Erlang/OTP is hosted on [github](https://github.com/erlang/otp), and jinterface is currently located in [this subdirectory](https://github.com/erlang/otp/tree/master/lib/jinterface)

The source it builds from has not been modified.

## Building a new version to target an OTP version

If there is no [published version] for the `OTP_VERSION` you want to
use, trigger a workflow here:

https://github.com/mechanical-orchard/jinterface/actions/workflows/build.yml

[published version]: https://github.com/orgs/mechanical-orchard/packages?repo_name=jinterface
