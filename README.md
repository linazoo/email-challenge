# email-challenge

<h1>HTML Email - Basic Rules</h1>
<h2>Notes:</h2>

<ul>
<li> HTML code should use tables to be sure your email layout renders correctly for ALL email clients.</li>
<li> HTML tables will be nested within HTML tables in order to build out every piece of your email</li>

<li> HTML tag properties should be used over CSS when possible, as the tag properties are more likely to be understood by email client engines. Many tag properties have been deprecated in HTML5 browsers in order to promote the use of CSS, so we don't use them on websites any longer, but all email client engines can still interpret the old HTML tag properties. (i.e. cellpadding / cellspacing for tables, < center > HTML tag for aligning your email body)</li>

<li> CSS should be inline, avoid external stylesheets</li>

<li> CSS3 should not be used, stick with old-style CSS rules to be sure ALL mail client engines understand it</li>

<li> You cannot write up HTML code, dump it into an outgoing email from your email account, hit Send, and expect it to render when it lands in someone's inbox. Mail clients do not allow HTML to be sent directly in this fashion, it's a security issue (hackers using code injection, viruses coded into emails, etc).  You have to have specific software to send HTML email, such as Constant Contact, Mailchimp, Interspire etc</li>
</ul>
 

 

<h2>Issues with the Challenge provided</h2>

<ul>
  <li> In a real job, I would have discussed first with the BP removing the comma in the headline, right after "chance". <em>"This is your last chance, to sign up for the service."</em> </li> 

<li> If not already in the email template, I would be sure an opt-out option is in the email footer to ensure all emails going out are CAN-SPAM compliant.</li> 

</ul>
