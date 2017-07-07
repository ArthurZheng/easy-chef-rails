source "https://supermarket.chef.io"

# basic cookbook for installing packages via apt
cookbook 'apt'

# creates users
cookbook 'users'

# requirement for 'users' cookbook when using knife solo
cookbook 'chef-solo-search'

# ssh daemon configuration
cookbook 'openssh'

# blocks IP addresses that try to brute force the server
cookbook 'fail2ban'

# enables passwordless sudo
cookbook 'sudo'

# 'Uncomplicated FireWall' for easy iptables setup
cookbook 'ufw'

# standard server tools
cookbook 'vim'
cookbook 'curl', git: "https://github.com/retr0h/cookbook-curl"

# the name of the following cookbooks says it all
cookbook 'chef_nginx', git: "https://github.com/chef-cookbooks/chef_nginx"
cookbook 'postgresql'
cookbook 'ruby_rbenv'
cookbook 'ruby_build'
cookbook 'build-essential', '~> 8.0.3'

# nodejs is required for rails asset compilation
cookbook 'nodejs'

# these packages are dependency for many common ruby gems
cookbook 'xslt'
cookbook 'libxml2'
cookbook 'imagemagick'

cookbook 'seven_zip'
