The following are the files and folders for contact importing. We are using cloudsponge for contact importing




app/etc/modules/Contact_Messages.xml
           - configuration xml

contactimporter
           - contains our style/images/js
userfiles
           - store the user messages as files
app/code/local/contact/
           - contains the controller
app/design/frontend/enterprise/bevel_shop/template/messages/
           - contains the contest tool templates.



Also need to add the following items in the cms block section
Admin -> CMS -> static blocks

      -- contest_welcome_message
      -- contest_welcome_title
      --  contest_mailbody
      --  contest_cloudsponge_apikey
      --  contest_thankyou