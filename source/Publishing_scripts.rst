Publishing scripts
==================

.. contents:: :local:
    :depth: 2

On TradingView it's possible to write custom indicators using Pine Script.
Users who write their own scripts can publish them to the :doc:`Public_Library` to share their
scripts with other users. Each published script gets a page with its
description, screenshot and source code, so users can see what the
script is about before applying it. If you want to protect your
indicator, you can use *Protected* and *Invite-Only* scripts, which hides
the source code from other users.

Publishing open source Pine Scripts
-----------------------------------

To publish an *open source* Pine indicator or strategy:

#. Open Pine Script Editor: |Pine_editor|
#. Open/write the script.
#. Apply the script to the current chart.
#. Click the *Publish Script* button: |Publish_script_button|
#. Select *Publish New Script* tab: |Publish_script_new|
#. Enter Script Title, Tags (optional), Description.
#. Click the *Publish Script* button.

The published script will be displayed in `Public Library <https://www.tradingview.com/script/>`__, 
which is available to all TradingView users. Every registered TradingView user will be able to make a copy of
your script.

Choosing a licence
------------------

Choosing a license or not is entirely up to you. You are under no
obligation to do so. If you publish scripts with open source code you
can select a license of your choice. You can include the license in
the comments section of a script (preferably in the beginning). Our
position on the matter is very much like that of
`GitHub <https://help.github.com/articles/licensing-a-repository/>`__.


Protected source code for Pine indicators
-----------------------------------------

It is possible to publish indicators with a *protected source code*. This is a
high-demand feature that lets you share knowledge and protect
intellectual property at the same time. These indicators are available
in the :doc:`Public_Library`, and any user can use them, but only the
author can see the source code. Each user can view, comment and favorite
the script's page with its description, screenshot and author's
comments. It's will available in the Public Library section in the
Indicators dialog, and any user can add this script to a chart. Only the
author can open the source code of protected scripts. This is a great
option for those who want to share the script, but protect its
calculation methods.

To make the indicator protected simply check *Protected Script* in the
script publication window:

|Protected_script_new|

Source code on charts is hidden from other users, so that only you will
see it until you decide to publish an open source version. Publish
ideas, send links to charts in chat --- your intellectual property remains
protected and no one will have access to your source code without your
decision.

Pine indicators with managed access
-----------------------------------

Authors can manage who can access their indicators. This is great for
commercial vendors, or authors who want to protect their IP, or share
with only a few select people --- the reasons could be many. If someone
wishes to sell indicators, the author may charge off-site for them, and
then provide access to the paying customers.

Simply choose the *Invite Only* option when publishing, and
only users who you specifically add will be able to use it.

|Invite_only_script_new| 

On the published script's page authors will see a *Manage Access* button, where you can add/remove
users, and manage access rights.

|Manage_access_button|

The invite-only indicators are visible in the :doc:`Public_Library`, 
but nobody can add it to a chart without
explicit permission from the author, and only the author can see the
source code. Each user can view, comment and favorite the script's
page with its description, screenshot and author's comments, and it's
available in the Public Library section in the Indicators dialog. Only
users with explicit permission from the author can add the script to a
chart. Nobody except the author can view the source code of these
scripts. This is a great option for commercial script vendors, or
authors who want to share the script only with a few select users. If
the author wishes to charge for access to these scripts, they may do
so off-site and then provide access to their customers. TradingView
does not require a percentage of the sales from such transactions. All
of your published scripts with limited access are shown in a new
section.

|Invite_only_tab|

.. |Pine_editor| image:: images/Pine_editor.png
.. |Publish_script_button| image:: images/Publish_script_button.png
.. |Publish_script_new| image:: images/Publish_script_new.png
.. |Protected_script_new| image:: images/Protected_script_new.png
.. |Invite_only_script_new| image:: images/Invite_only_script_new.png
.. |Manage_access_button| image:: images/Manage_access_button.png
.. |Invite_only_tab| image:: images/Invite_only_tab.png

