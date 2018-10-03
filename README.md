try to set up a host-only network. !error:
未能创建主机网络连接.  VBoxNetAdpCtl: Error while adding new interface: failed to open /dev/vboxnetctl: No such file or directory.  返回 代码: NS_ERROR_FAILURE (0x80004005) 组件: HostNetworkInterfaceWrap 界面: IHostNetworkInterface {455f8c45-44a0-a470-ba2
reference:https://stackoverflow.com/questions/18149546/vagrant-up-failed-dev-vboxnetctl-no-such-file-or-directory


sudo "/Library/Application Support/VirtualBox/LaunchDaemons/VirtualBoxStartup.sh" restart 

worked!
