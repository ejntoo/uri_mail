UriMail
=======

UriMail or uri_mail is a Textpattern 4.5 plugin.
It lets you create a contact form in the front-end where visitors of your website can send private messages to the administrator.


Compiling
---------

To compile it, you need Textpattern extension ied_plugin_composer:
1. In the Plugin composer tab, write "uri_mail" in the "name" field and click on "Create new plugin";
2. Paste the main file content (the PHP code) in the "Plugin code" textarea;
3. In the bottom of the page, choose Distribution > Export as uri_mail_v*.*.txt.
The downloaded file will be the compiled project, ready to be installed as any Textpattern plugin.


Usage
=====

What to do after the installation
---------------------------------

After installing the plugin, go to the Extensions tab and select the UriMail subsection: the plugin will create a database table to store the messages.
You should see an empty table, because there's no content yet.

Tags, i.e.: how to use
----------------------

The most simple tag is <txp:uri_mail />, that creates a simple form with the three main fields.

Tag parameters, i.e.: how to customize
-------------------------------------

There are three parameters that let you change the label of the three fields:
* mail_label, that changes the label of the email field; its default value is "Your email".
* object_label, that changes the label of the object field; its default value is "Object".
* message_label, that changes the label of the message textarea; its default value is "Your message".
* send_label, that changes the label of sumit button.
* success_message/failed_message, that change the success/error response.

Managing the messages
---------------------

When you visit the UriMail tab in the Extensions section, you can see the messages sent to you; clicking on a line lets you see the complete text, with also a link to delete the messages you don't need any more.
