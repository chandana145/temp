##Left Nav Bar
<nav ng-controller="MainNavController"
			class="navbar-default navbar-static-side" role="navigation">
			<div class="sidebar-collapse">
				<ul class="nav" id="side-menu">

					<li class="active"><a ng-click="goHome()"><i
							class="fa fa-th-large"></i><span id="subMenuLabel"
							class="nav-label">Login</span></a></li>

				</ul>
			</div>
		</nav>
		
		




# temp

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
