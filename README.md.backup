# GRUB Themes

## 中文说明：

该仓库为各发行版之中提取出来的`GRUB`主题。

> **提示：**</br>
>  `starfield`为`GRUB`的图形化菜单的默认主题；</br>
>  `bliss`为`Bliss OS`启动时的`GRUB`主题；</br>
>  `deepin`为`deepin V20`启动时的GRUB 主题；</br>
>  `manjaro-live`为`Manjaro`系统安装启动时的`GRUB`主题；</br>
>  `ukylin`为`优麒麟 20.04 LTS`启动时的`GRUB`主题。

### 如何使用

- ① 将喜欢的`GRUB`主题复制到`/boot/grub/themes/`目录。

   > 若 `themes` 目录不存在，则使用如下命令创建该目录：
   > 
   > ```shell
   > $ sudo mkdir -pv /boot/grub/themes
   > ```
   > 
   > 并给 `themes` 目录分配适当的权限：
   >
   > ```shell 
   > $ sudo chown $USER /boot/grub/themes/
   > ```

- ② 在`/etc/default/grub`文件中找到`GRUB_THEME=` ，</br>并在其后添加喜欢的主题的`theme.txt`，</br>且需取消`GRUB_GFXMODE=`注释，以输入背景图像分辨率，</br>具体修改如下所示：

  ```shell
    [...]
    GRUB_THEME=/boot/grub/themes/<主题名称>/theme.txt
    GRUB_GFXMODE=<分辨率>
    [...]
  ```
  
  > **注意：**</br>
  > 以防万一，更改前请备份`GRUB`文件。

- ③ 使用如下命令更新`GRUB`：

  ```shell
  # Debian及其发行版
  $ sudo update-grub
  # 或者
  $ sudo update-grub2
  
  # Red Hat/CentOS/Fedora及其发行版
  $ sudo grub-mkconfig -o /boot/grub/grub.cfg
  # 或者
  $ sudo grub2-mkconfig -o /boot/grub2/grub.cfg
  
  # ArchLinux及其发行版
  $ sudo grub-mkconfig -o /boot/grub/grub.cfg
  ```
  
- ④ 若删除手动安装的`GRUB`主题，</br>则需删除复制到`/boot/grub/themes/`目录的文件夹，</br>注释或删除`/etc/default/grub`文件中`GRUB_THEME`与`GRUB_GFXMODE`参数</br>并更新`GRUB`即可，</br>即原路返还。

### 主题推荐

-  [vinceliuice/grub2-themes](https://github.com/vinceliuice/grub2-themes)

-   [Teraskull/bigsur-grub2-theme](https://github.com/Teraskull/bigsur-grub2-theme)

-  [shvchk/poly-light](https://github.com/shvchk/poly-light) 或者 [OpenDesktop：shvchk/poly-light](https://opendesktop.org/p/1176413)

-  [xenlism/Grub-themes](https://github.com/xenlism/Grub-themes) 

## English description：

This repository is the `GRUB` theme extracted from each distribution.

> **Hint:**</br>
> `starfield` is the default theme for `GRUB's` graphical menu;</br>
> `bliss` is the` GRUB `theme of` Bliss OS` startup</br>
> `deep `is the GRUB theme when` deep V20 `starts</br>
> `manjaro live `is the` GRUB `theme when the` Manjaro `system installation starts</br>
> `ukylin` is the `GRUB` theme of `Ukylin 20.04 LTS` startup.

### How to use

- ① Copy your favorite `GRUB` theme to the `/boot/grub/themes/` directory.
> If the `themes` directory does not exist, use the following command to create it:
> 
> ```shell
> $ sudo mkdir -pv /boot/grub/themes
> ```
> 
> Assign appropriate permissions to the `themes` directory:
>
> ```shell 
> $ sudo chown $USER /boot/grub/themes/
> ```

- ② Find `GRUB_THEME=` in the `/etc/default/grub` file,</br>and add the theme of your favorite theme Txt ,</br>and cancel `GRUB_ GFXMODE=` Comment to input the background image resolution.</br>The specific modifications are as follows:


  ```shell
    [...]
    GRUB_THEME=/boot/grub/themes/<Topic Name>/theme.txt
    GRUB_GFXMODE=<resolving power>
    [...]
  ```
  
- ③ Use the following command to update `GRUB`:

```shell
# Debian and its distribution
$ sudo update-grub
# Or
$ sudo update-grub2

# Red Hat/CentOS/Fedora and its distribution
$ sudo grub-mkconfig -o /boot/grub/grub.cfg
# Or
$ sudo grub2-mkconfig -o /boot/grub2/grub.cfg

# ArchLinux and its distribution
$ sudo grub-mkconfig -o /boot/grub/grub.cfg
```

- ④ If you delete the manually installed `GRUB` theme,</br>you need to delete the folder copied to the `/boot/grub/themes/` directory,</br>comment or delete the `GRUB_THEME` in the `/etc/default/grub` file  and ` GRUB_ GFXMODE ` parameter </br> and update ` GRUB `.</br>means original return.

### Topic recommendation

-  [vinceliuice/grub2-themes](https://github.com/vinceliuice/grub2-themes)

-   [Teraskull/bigsur-grub2-theme](https://github.com/Teraskull/bigsur-grub2-theme)

-  [shvchk/poly-light](https://github.com/shvchk/poly-light) or [OpenDesktop：shvchk/poly-light](https://opendesktop.org/p/1176413)

-  [xenlism/Grub-themes](https://github.com/xenlism/Grub-themes) 