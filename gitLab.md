### gitLab 忘记用户密码操作

> 进入GitLab 控制台命令		
>
> ​	gitlab-rails console production
>
> 通过用户名查找用户,获取用户ID	 	
>
> ​	user = User.where(username:'test').first
>
> 通过用户ID获取用户	 	
>
> ​	user = User.where(id:22).first
>
> 修改密码,建议通过ID找到用户后在执行修改密码		
>
>  	user.password='1q2w3easd2'
>
> 保存 			
>
> ​	user.save! 









