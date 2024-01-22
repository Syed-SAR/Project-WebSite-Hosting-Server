<h2>Project:Setting up Website locally on Linux machine</h2>
<h3 align="left">Languages and Tools:CentOS7, Vagrant, GitBash, Website</h3>
<p align="left">
  <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer">
    <img
      src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg"
      alt="bash"
      width="40"
      height="40"
    />
  </a>
  <a href="https://git-scm.com/" target="_blank" rel="noreferrer">
    <img
      src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg"
      alt="git"
      width="40"
      height="40"
    />
  </a>
  <a href="https://www.linux.org/" target="_blank" rel="noreferrer">
    <img
      src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg"
      alt="linux"
      width="40"
      height="40"
    />
  </a>
  <a href="https://www.vagrantup.com/" target="_blank" rel="noreferrer">
    <img
      src="https://www.vectorlogo.zone/logos/vagrantup/vagrantup-icon.svg"
      alt="vagrant"
      width="40"
      height="40"
    />
  </a>
</p>
<ul>
  <li>To set up a website on linux server you need a Web server running which could be
    HTTPD for CentOS/RHEL or Apache2 for Ubuntu</li>
    <li>Install packages like wget, git,
        zip, unzip, etc. if needed</li>
        <li>Start and Enable the Server Copy the website into the
            designated folder like /var/www/html for HTTPD service with “index.html” file</li>
            <li>Check the IP address if setup locally and verify it on a browser</li>
            <li>All these steps
                can be automated by provisioning in the Vagrant file during bootup itself</li>
</ul>
