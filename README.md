# Roundcube Attachment Preview

Preview attachment in message area instead of new tab.

## Usage
The plugin adds an option to the attachment menu, so you can preview the attachment right within the message area:

<img src="docs/attachment_menu.png" alt= “” width="400px" height="112px">

## Install
Execute the following lines in your Roundcube plugins folder
~~~
wget -q https://github.com/jv-barsuk/roundcube_attachment_preview/archive/refs/heads/main.zip -O attachment_preview.zip; unzip attachment_preview.zip; mv roundcube_attachment_preview-main attachment_preview; rm attachment_preview.zip
~~~

add the plugin `'attachment_preview',` to the plugins list in your roundcube config file `config/config.inc.php`:
~~~
$config['plugins'] = array(
        'carddav',
        'persistent_login',
        'attachment_preview',
);
~~~
