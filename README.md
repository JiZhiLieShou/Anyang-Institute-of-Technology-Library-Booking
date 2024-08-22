<p><a href="https://github.com/JiZhiLieShou/Anyang-Institute-of-Technology-Library-Booking"><img width="100%" src="https://github.com/JiZhiLieShou/Anyang-Institute-of-Technology-Library-Booking/blob/main/%E9%BB%91%E5%A4%9C%E4%BD%BF%E8%80%85.webp" ></a></p>

**未加入多线程操作，后来者可以看着改**


此外，我还研发了一系列程序，这些功能旨在提升用户体验，确保系统的智能性和安全性。

- 取消所有预约
- 图书馆加密算法小工具
- 座位监控
- 循环卡位置（适用于赖床或不愿签到的用户）
- 文字识别方式（可灵活拓展）
- 查看随机座位
- 预约座位（不带验证码）
- 预约座位（带验证码）。
## 使用方式：

1. 在information中填入你的信息

2. 在下午8点之前开启脚本

3. 座位号填写：

   - 注意格式！

   - 楼层对应：

     1. 一楼

        一层A区：'1A'

        一层B区：'1B'

        一层C区：'1C'

        一层D区：'1D'

     2. 五楼:'05'

   - 格式：楼层 排 号

   - 如:

     1. 一楼C区四排三号：1C0403

4. 停顿时间：5秒一次最为合适

## TXT文件解释说明：


1. ### seat.txt      

   图书馆座位号与位置的编码信息  一般不需要修改

2. ### information.txt 你的信息

   - 图鉴识别账号：
   - 图鉴识别密码：
   - 停顿时间：5
   - 座位号：1B0807
   - 图书馆用户名：
   - 图书馆密码：
   - 预约开始时间：2023-10-20 07:00
   - 预约结束时间：2023-10-20 22:30
   - 是否需要阻塞时间：0
   - 阻塞时间：20:00:00

## 图鉴打码平台：

- `图鉴：http://www.ttshitu.com/login.html`

## 注意事项：

- 直接报错，闪退：代码运行时不要开vpn(连美国地址怎么去访问图鉴识别站点)

## 报错集锦：

- [1001]：预约速度过快
- invid：cookies错误，网站连接或者加密方式更新
- 校验码错误：预约实时时间死板了（time变量）




## 特别声明：此系统仅供个人学习、研究之用，请勿用于商业用途，如果使用本项目出现任何问题与本人无关”。请在下载后24小时内删除。
