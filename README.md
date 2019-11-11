## MasterOJ

### Description

MasterOJ is an online informatics evaluation system based on webpage. It was launched on February 13, 2019, providing OIers with a beautiful online evaluation platform. Users can not only do questions here, but also express their opinions, communicate with each other and experience new technologies. In order to attract OIer, we have also developed a number of Apps, which are placed on this OJ. For everyone to experience for free. Rich question bank: I have most of the topics of CF, LOJ, NOIP, and are constantly improving. Thanks zhblue for their support of this OJ.

This OJ is based on Hustoj development. Developed with Bshark theme (by Yemaster)

If this project is useful to you, please:

 - Wave the mouse and give Star in the upper right corner!
 - Recommend this project to my classmates and colleagues
 - Support us to let us better maintain and develop this project
 
### Software version
 
Hustoj(支持2019年4月到现在的所有版本) - 仅使用评测机

Tips: You can manually update the Hustoj version, but we won't solve any problems due to incompatible versions.

### Update log

#### 2019.11.10

 1. Fix blog bugs and re-launch
 2. Fix other bugs
 
#### 2019.10.29

 1. Optimize the user interface
 2. Modify custom features to allow custom css code
 3. Picture bed function online
 
#### 2019.9.25

 1. Allow github login, users can view github information

#### 2019.8.15

 1. The contests allows modification of the OI and ACM modes.
 2. Increase the home page big picture carousel, add aesthetics
 3. Modify the navigation bar

#### 2019.8.11
 
 1. Provide custom OJ styles

#### 2019.7.24
 
 1. Update to BShark theme， completely independent research and development
 2. Rewrite the forum, more rich features
 3. Rewrite the background interface, named bsadmin
 4. Increase background permissions
  
#### 2019.7.11
 
 1. VIP function is online
 2. Message board function is online
 3. Blog function is online
 4. The solution function is online
 5. Fix other bugs

#### 2019.6.30

 1. Increase the score function
 2. Modify the bottom style

#### 2019.4.27

 1. We completed the infrastructure of this OJ and successfully installed it on the server.
 2. Complete the basic meto theme (non-independent R&D)
 
### Installation

#### Precautions

Don't believe that Baidu's long-formed so-called tutorials, those are the old emperors of a few years ago, will lead to no judgment, no display, not easy to upgrade and so on.

Especially do not install apache, if it has been installed, please disable or uninstall first, so as to avoid 80 port conflicts.

Do not use the Mysql Nginx Apache PHP environment provided by LNMP/LAMP/Cpanel/ other panel programs. The installation script already contains installations for all required environments.

Tencent cloud users please change the software source and increase the multiverse.

Aliyun users please Baidu "Alibaba Cloud 80 port"

#### Installation dependencies

Need to install hustoj first (Visit [https://github.com/zhblue/hustoj#hustoj----%E6%B5%81%E8%A1%8C%E7%9A%84oj%E7%B3%BB%E7%BB%9F%E8%B7%A8%E5%B9%B3%E5%8F%B0%E6%98%93%E5%AE%89%E8%A3%85%E6%9C%89%E9%A2%98%E5%BA%93](https://github.com/zhblue/hustoj#hustoj----%E6%B5%81%E8%A1%8C%E7%9A%84oj%E7%B3%BB%E7%BB%9F%E8%B7%A8%E5%B9%B3%E5%8F%B0%E6%98%93%E5%AE%89%E8%A3%85%E6%9C%89%E9%A2%98%E5%BA%93) for more information)

#### Formal installation

 1. Download the latest version of the MasterOJ web package and save it as /home/judge/src/web.tar.gz
```plain
TODO
```
 2. Go to the directory, back up the original web, unzip web.tar.gz
```bash
cd /home/judge/src
mv ./web ./web-old
tar -zxvf web.tar.gz
```
 3. Configure the database. For details, see db_info.inc.php in the original web (web-old).
 4. Delete the original jol database and import the downloaded sql file
 5. Download the nginx config file.Back up the original configuration file and replace it, restart nginx。Don't forget to set to your own configuration.
```bash
nginx -s reload
```
 
