# captcha
生成验证码图片

一、generate_image函数说明
  参数： chars: 验证码中内容
        rotate: bool,  是否旋转字符
        warp: bool, 是否扭曲字符
        noise_curve: bool, 是否添加曲线干扰
        noise_dots: bool, 是否添加点干扰
        noise_dots_width: int, 点噪声宽度
        noise_dots_number: int, 点噪声数量
