# testvegi
testing markup

### to build gateone with packer run 
` packer build --var 'distro=distro_name' --var 'version=xenial' gateone.json `

### upload gateone wheel packages to s3

'python s3.py --distro distro_name --version xenial'


