# Hi, I'm Robert Gardam

I build infrastructure and developer tooling: the platforms, pipelines and
clusters that other engineers ship on. I like making them fast to build and
easy to scale.

Right now that's [Backstage](https://backstage.io), the developer portal:
running it as separate services that each build, release and scale on their
own, so it keeps up as an organisation grows.

I also like chasing a problem down to its root cause and writing up what I
found, from slow builds to Bluetooth audio that keeps dropping out on Linux.

## Projects

- **[multi-deployment-backstage](https://github.com/rgardam/multi-deployment-backstage)**:
  Backstage as separately built, released and scaled services behind one
  gateway, with the software catalog split across several instances.
- **[airpods-linux-audio-fix](https://github.com/rgardam/airpods-linux-audio-fix)**:
  a fix for AirPods and other Bluetooth audio dropping out on Ubuntu with
  PipeWire and BlueZ. The cause was Bluetooth sniff mode, not the codec,
  buffers or kernel. Includes a write-up and an install script.
- **[mbp2013-ubuntu-broadcom](https://github.com/rgardam/mbp2013-ubuntu-broadcom)**:
  fixes for the Broadcom wireless drivers on a 2013 MacBook Pro running
  Ubuntu.
- **[aws-swarmer](https://github.com/rgardam/aws-swarmer)**: a Terraform module
  that deploys a working Docker Swarm cluster on AWS.

## Tools

TypeScript and Node.js, Docker, Terraform, AWS, Linux and shell scripting.
