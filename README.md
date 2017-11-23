# Multi-paged Survey with sessions
<p><a href="http://lianxiao.dev.fast.sheridanc.on.ca/xiaoyu/SurveyWithSessions/index.php">Try it</a></p>
<ul>
  <li>Use FormValidation2 as base. Add interactive checking with JavaScript, much as I did in FormValidation1, only using regular expressions this time.</li>
  <li>Every time user move away from a field, an onblur event to validate the field.</li>
  <li>Once all of the data has been validated correctly, instead of displaying it on this screen, direct them to a second .php file called saveData.php. Make use of sessions to store this information.</li>
  <li>This second page will show user's information to the screen. Below this, provide them with a button that will save their information to a .txt file. The file will be named FirstName_LastName.txt and saved to a subfolder called users. Each field should be saved on a new line.</li>
  <li>Give user a message stating that the file has been saved successfully.</li>
</ul>
<h2>Why add JavaScript</h2>
<p>It’s easier to give quick feedback on a form with JavaScript. However, JavaScript can be disabled on any browser! That’s why we need to check again on the server.</p>
