
# Uncomplicated VM Tools (uvt)

uvt is essentially a wrapper script for virsh and virt-install for both
making VM creation repeatable and to help batch commands to multiple VMs.

IMPORTANT: **This snap should not be used by the general audience**.
VMs created by uvt use intrinsically insecure configurations and uvt code
is not checked for vulnerabilities. Thus, general use of uvt may pose a
security risk for your system and should be avoided by all means. uvt is
only intended to be used by the Ubuntu Security team to generate ephemeral
environments to test security patches in a consistent way.