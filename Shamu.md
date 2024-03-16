<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
<meta charset="utf-8" />
<meta http-equiv="X-UA-Compatible" content="IE=edge" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Car Rental System</title>

<!-- Global stylesheets -->
<link href="https://fonts.googleapis.com/css?family=Roboto:400,300,100,500,700,900" rel="stylesheet" type="text/css" />
<link	href="Template/assets/css/icons/icomoon/styles.css"	rel="stylesheet" type="text/css" />
<link href="Template/assets/css/bootstrap.css" rel="stylesheet" type="text/css/>
<link href="Template/assets/css/core.css" rel="stylesheet" type="text/css" />
<link	href="Template/assets/css/components.css"	rel="stylesheet" type="text/css" />
<link href="Template/assets/css/colors.css" rel="stylesheet" type="text/css" />
<!-- /global stylesheets -->

<!-- Core JS files -->
<script	type="text/javascript">
src="Template/assets/js/plugins/loaders/pace.min.js"</script>
<script	type="text/javascript">
src="Template/assets/js/core/libraries/jquery.min.js"></script>
<script	type="text/javascript">
src="Template/assets/js/core/libraries/bootstrap.min.js"></script>
<script	type="text/javascript">
src="Template/assets/js/plugins/loaders/blockui.min.js"></script>
<!-- /core JS files -->
<script type="text/javascript" src="Template/assets/js/core/app.js"></script>
</head>
</head>
<body class="login-container">
<form id="form2" runat="server">
<div class="navbar navbar-inverse">
<div class="navbar-header">
</div>
</div>
<div class="page-container">
<div class="page-content">
<div class="content-wrapper">
<div class="panel panel-body login-form">

<div class="text-center">
<div	class="icon-object	border-slate-300	text-slate-300"><i	class="icon- user"></i></div>
<h5 class="content-group">Welcome Admin <small	class="display-block">Your credentials</small></h5>
</div>

<div class="form-group has-feedback has-feedback-left">
<asp:TextBox	ID="txt_Uname"	runat="server"	CssClass="form-control" placeholder="Enter Email" required=""></asp:TextBox>
<div class="form-control-feedback">
<i class="icon-user text-muted"></i>
</div>
</div>
<div class="form-group has-feedback has-feedback-left">
<asp:TextBox	ID="txt_Pwd"	runat="server" TextMode="Password" placeholder="Enter Password" CssClass="form-control" required=""></asp:TextBox>
<div class="form-control-feedback">
<i class="icon-lock2 text-muted"></i>
</div>
</div>
<div class="form-group login-options">
<div class="row">
<div class="col-sm-6">
</div>
<div class="col-sm-6 text-right">
</div>
</div>
</div>
<div class="form-group login-options">
<div class="row">
<div class="col-sm-6">
<label class="checkbox-inline">
<asp:CheckBox ID="Chk_rem" runat="server" CssClass="styled" />

</label>
</div>

<div class="col-sm-6 text-right">
<a href="Forgotpassword.aspx">Forgot password?</a>
</div>
</div>
</div>
<div class="form-group">
<asp:Button ID="btn_Submit" runat="server" CssClass="btn btn-primary btn-block" Text="Login" OnClick="btn_Submit_Click" />
</div>

<div id="div_error" runat="server" class="alert alert-danger" visible="false">
<button type="button" class="close" data-dismiss="alert"><span>&times;</span>
<span class="sr-only">Close</span></button>
<asp:Label ID="lbl_error" runat="server"></asp:Label>
</div>
</div>
</div>
</div>
</div>
</form>
</body>

</html>
