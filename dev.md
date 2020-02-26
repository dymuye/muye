# muye java开发环境检查

# 查看JDK版本
java -version
根据项目要求核对jdk版本，升级或更新都需要重新安装


# 查看git版本
git --version
# git版本升级
git clone https://github.com/git/git

#查看maven版本
mvn -v

#查看环境变量
echo $PATH
#添加环境变量
export PATH="/opt/STM/STLinux-2.3/devkit/sh4/bin:$PATH"
#环境变量立即生效
source .bash_profile   (source后面跟的是环境变量路径及名称)




