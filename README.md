Utility to change EBS volume types and IOPS

The utility will stop the instance (if it was not stopped), and -in parallel- will create snapshots for the designated volumes, detach volumes, destroy them, create new volumes from the snapshots, attach them and finally will start the instance (if it was started in the beginning).

**Requirements**

You will need at least Python2.6, and colorama and boto modules before running the script.

**Use**

Run ebs-changer *--help* to know how to use it.
