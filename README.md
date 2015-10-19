# temp
<div class="container">
    <div class="row">
        <div class="col-sm-6 col-md-4 col-md-offset-4">
            <h1 class="text-center login-title">Sign in to continue to Bootsnipp</h1>
            <div class="account-wall">
                <img class="profile-img" src="https://lh5.googleusercontent.com/-b0-k99FZlyE/AAAAAAAAAAI/AAAAAAAAAAA/eu7opA4byxI/photo.jpg?sz=120"
                    alt="">
                <form class="form-signin">
                <input type="text" class="form-control" placeholder="Email" required autofocus>
                <input type="password" class="form-control" placeholder="Password" required>
                <button class="btn btn-lg btn-primary btn-block" type="submit">
                    Sign in</button>
                <label class="checkbox pull-left">
                    <input type="checkbox" value="remember-me">
                    Remember me
                </label>
                <a href="#" class="pull-right need-help">Need help? </a><span class="clearfix"></span>
                </form>
            </div>
            <a href="#" class="text-center new-account">Create an account </a>
        </div>
    </div>
</div>



<form action='' method='POST'><table>
						<tr>
		                 	<td>
		              			<div>
		       		 				<label>Email:</label>
              		 			</div>
					 		</td>
		         			<td>
		                 		<div>
		                  			<input type='email' id='login_email' value=''/><br>
						         	<div id='login_email_errorloc' class='error_strings'></div>
		               			</div>
		  					</td>
		                 	<td>
		        				<div>
		  		 					<label>Password:</label>
			              		 </div>
		                 	</td>
		                 	<td>
		                 		<div>
			                 		 <input type='password' id='login_password' class=''></input>
									 <div id='login_password_errorloc' class='error_strings'></div>
		                 	    </div>
		                 	</td>
							<td>
								<input type='submit' value='Sign in' id='signin' class='loginButton' onclick='Register.processLogin();return false;'>
						 	</td>
		                </tr>
						<tr>
							<td>
							</td>
							<td>
							</td>
							<td>
							</td>
							<td>
						 		<a href='p/reset.php' style='font-size:14px;'>Forgot password?</a>
						 	</td>
						 	<td>
							</td>
						</tr>
					</table></form>
					
					
					
					
					
					
					
					####Mnaoj Version
					<form action='' method='POST'>
			<div class="  form-inline"
				ng-class="{ 'has-error': form.username.$dirty && form.username.$error.required }">

				<label for="username">Username</label> <input type="text"
					name="username" id="username" ng-model="vm.username" required /> <span
					ng-show="form.username.$dirty && form.username.$error.required"
					class="help-block red-text-form">Username is required</span>

			</div>
			<div class="  form-inline"
				ng-class="{ 'has-error': form.password.$dirty && form.password.$error.required }">
				<label for="password">Password</label> <input type="password"
					name="password" id="password" ng-model="vm.password" required /> <span
					ng-show="form.password.$dirty && form.password.$error.required"
					class="help-block red-text-form">Password is required</span>
			</div>
			<button type="submit" class="btn btn-primary">Login</button>
			

			<!-- Main Content -->
			<!-- embedded alert message box -->
			<div class="col-lg-6 " ng-show="showErrorMsg"
				ng-class="{'red-text-form': isErrorMsg}">
				<strong>{{errorMsg}}</strong>

			</div>
			
			</form>
			
			
			###End of manoj version
