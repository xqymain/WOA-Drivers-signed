
# Windows Drivers for Qualcomm Snapdragon platforms

This repository contains driver binary files for Qualcomm Snapdragon platforms.

# How to use 如何使用？

**Please run the following command before deploying drivers!**

**请在安装驱动前执行下列命令！！**

其中DEVICE为设备代号！务必确认！

```
.\extract.ps1 DEVICE
```

or

```
./extract.sh DEVICE
```
# Important modification 重要的改动

初次安装系统请按照教程操作，进入系统后合并项目根目录的`EVRootCA.reg`以信任时间戳服务器。随后即可关闭`测试模式`和`禁用驱动强制签名`。

Please follow the tutorial to install the system for the first time. After entering the system, merge the `EVRootCA.reg` in the project root directory to trust the timestamp server. Then you can turn off `Testsigning` and `Disable driver signature enforcement`.

**该操作可能会使你遭受中间人攻击**

**如果你不了解你在做什么，请使用Renegade Project原版驱动**

**This operation may expose you to a man-in-the-middle attack**

**If you don’t understand what you are doing, please use the original Renegade Project driver**

## Copyright, License, Disclaimers and end user license agreement

**Below notice must be present in all redistributed portions of this software**

Copyright (c) 2020-2021 Renegade Project

Copyright (c) 2017-2020 WOA-Project

Copyright (c) 2012-2019 Qualcomm Incorporated


This repository contains binary files, most of which are not made by us and were found on SDM850 laptops,  

- By installing this driver pack, you agree that any damage done to your phone or any loss of data is your entire responsibility and we cannot be taken responsible for data loss if it ever happens. We believe however this driver pack is safe to install. Try at your own risk!

- Charging an extra fee for a phone where you would have installed those drivers and you are selling online or to users is immoral and illegal due to where those drivers come from. An end user may not know how to update their system in the future and will most likely spent a lot more than what it should have for a driver pack he can find for free online. Selling a device with an extra fee also ruins the work of others that worked on this project. While we can't enforce this policy, we decided to put this notice here in the hopes of some people understanding the morality of this.


**Contributors**

We would like to thank the following people that helped:

```
- Lemon1ice

- NTAuthority

- gus33000

- imbushuo

- strongtz

- TAO_Croatia

- wetdreams

- Our testers, you know who you are :)

- Qualcomm and Microsoft

- .......
```

The above copyright notice and this permission notice shall be included in all

copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR

IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,

FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE

AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER

LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,

OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE

SOFTWARE.


## Project Status

[Device Support Status](https://renegade-project.org/#/en/windows/state-frame.html)

## Cloning

For preserving charset encoding, please checkout with using:

```
git clone -c core.autocrlf=false https://github.com/edk2-porting/WOA-Drivers
```
