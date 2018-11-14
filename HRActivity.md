
<html>

<head>
<meta content="text/html; charset=utf-8" http-equiv="Content-Type">
<style type="text/css" rel="stylesheet">

body {
    margin: 0;
    padding: 0;
}

div.nuit {
    margin: 0;
    background: #FFFFFF;
    padding: 10px;
}

table.nuit {
    width: 650px;
}

td.nuit {
    width: 100%;
    border: 2px solid #333;
    background: #FFFFFF;
    padding: 15px 15px 10px 15px;
    color: #333;
}

td.nuit a:link, td.nuit a:visited {
    color: #007199;
    text-decoration: none;
}

td.nuit a:active {
    color: #F5800F;
    text-decoration: none;
}

td.nuit a:hover {
    color: #F5800F;
    text-decoration: underline;
}

td.nuit a img {
    border: 0;
}

td.nuit h1 {
    margin: 0 0 4px 0;
    width: 100%;
    border-bottom: 1px solid #515151;
    color: #515151;
    font: bold 14pt Calibri, Arial;
}

td.nuit h2 {
    margin: 25px 0 0 0;
    width: 100%;
    border-bottom: 1px solid #aaa;
    color: #515151;
    font: bold 12pt Calibri, Arial;
}

td.nuit p, td.nuit pre {
    margin: 8px 0 6px 0;
    font: 11pt Calibri, Arial;
}

td.nuit pre {
    white-space: pre-wrap;
}

td.nuit p.link {
    margin-top: 12px;
    font-size: 12pt;
    font-weight: bold;
}

td.nuit p.footer {
    margin-top: 10px;
    text-align: center;
    color: #666;
}

td.nuit em {
    font-style: normal;
}

td.nuit strong {
    font-weight: bold;
}

td.nuit hr {
    height: 1px;
    border: 0;
    border-top: 1px solid #aaa;
    margin: 25px 0 6px 0;
}

.auto-style1 {
	color: #3EB049;
}

.auto-style2 {
	font-weight: normal;
	color: #FF0000;
}

</style>
</head>
<body>
<div class="nuit">
<table cellspacing="0" class="nuit"><tr><td class="nuit">
<h1><span class="auto-style2"><strong>Action Required!</strong></span> New Hire Task has been assigned to your group.
</h1>
  <p>You can review this {Class/Title} by clicking </a>
<a href="{$ApplicationSetting.ProcessApprover.WebAccessApproverURL$}">HERE</a>.<br><br>
<p><em>
</em></p>
<h2>New Hire Details</h2>
 <p><span class="auto-style2"><strong>Start Date:</strong> {_NHStartDateShort}</span> </p>
<p><strong>Name: </strong> <span class="auto-style1"><strong>{_NHLastName} {_NHFirstName}</strong></span></p>
<p><strong>Location:</strong> {_NHUserLocation}</p>
<p><strong>Department: </strong> {_NHUserDepartment}</p>
<p><strong>Company: </strong> {_NHUserCompany}</p>

<p><strong>Manager:</strong> {_NHUserManager}</p>

</td>
</tr>
</table>
</div>
</body>
</html>

