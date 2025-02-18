# docker-course
> Note: You should have admin permission in your workstation to make Virtaualbox work.

Download and install virtual box from https://www.virtualbox.org/wiki/Downloads

## Install Vagrant

Install Vagrant followin insructions from https://developer.hashicorp.com/vagrant/downloads

## Restart the System

Once all the installation is done, restart the system.

## Bring up the VM

Clone the docker course repo.

```
git clone https://github.com/techiescamp/docker-course.git
```

Now, open the terminal and cd in the docker-course/lab-setup.

```
cd docker-course/lab-setup
```

Execute the following command to bring up the VMs

```
vagrant up
```
Check the vm status using the following command. You should see  VM in running state.

```
vagrant status
```

Once the VMs are up, you cna login to the VM using the VM name.

```
vagrant ssh Docker 
```

## Halt the VMs

When you are not using the setup, you can halt the VMS to free up the CPU and memory in your system using the halt command.

```
vagrant halt
```

## Destroy the setup

You can destroy the VMs usin the following command.

```
vagrant destroy -f
```