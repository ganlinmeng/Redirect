# Redirect
重定向<br>
可以这样引用<br><br>
 [ChongDingXiangViewController initWithPath:@"http://wwc.taobaocdn.com/avatar/getAvatar.do?userNick=\\U56de\\U8f66\\U95f4&width=80&height=80&type=sns" completion:^(NSURL *url, NSError *error) {
            dispatch_async(dispatch_get_main_queue(), ^{
               [_userImage sd_setImageWithURL:url];
            });
    } error:^(NSError *error) {
        
    }];
