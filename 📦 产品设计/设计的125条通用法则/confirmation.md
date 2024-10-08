# 设计的125条通用法则
## 确认

一种在生效前需要先确认，避免失误的技巧。<sup>1</sup>

> <sup>1</sup>也称为验证法则（verification principle）和强制功能（forcing function）。

![](/SCR-20240525-hfej.png)

确认是运用在关键的行动、输入信息或下达指令时的一种技巧。它的功能是确认我们的行动或输入是否正确。主要用来防止“疏忽”这种错误，也就是防止出自非本意的行为。它会减缓工作效率，用于关键性或无法挽回的操作上。当行动的后果不严重，或者可以轻易地完全挽回，就无须采用确认功能。确认法则有两种基本技巧：对话式、两步操作。

使用对话式确认，必须与系统使用者建立互动对话。最常见的是，出现在软件显示的对话框（例如“你确定要删除所有档案吗？”），对话框提示使用者是否要执行此命令。对话信息务必简明扼要，但要能正确详细地传达出行动的后果。信息应该以一个问题作结束，设计成让使用者点击“是”或“否”，或者用一个动词表明下一步动作（在确认中，应该避免使用“好”或“取消”）。对于不重要的确认信息，应该要有“取消确认”的功能选项。

两步操作确认，是指必须在确定命令下达或输入信息之前，先出现一个预备步骤。这个方法最常见于硬件操作，通常指的是“上膛/发射”动作。换句话说，首先你要装上零件，然后发射（执行）它。举例来说，在启动开关前，可能要先掀起开关盖；可能两个人必须一起转动两把特制钥匙，才能发射核武器；或者是太空船的一个操控杆，可能需要先转动后再按下开关才能启动。两步操作的目的，为了防止意外启动重要控制开关的错误发生。如果只有在两步操作步骤完成后才能启动，意外启动的状况就不太可能发生。两步操作常用于飞机、核电厂、其他危险操作环境里的重要作业项目。

在重要或无法挽回的操作中应用确认法则，尽量把错误降到最低。但不要过度使用确认，确保使用者不会忽略它。硬件的确认，可使用两步操作技巧；软件的确认，则可使用对话框。针对不太重要的命令，可允许使用者于首次确认之后，能够取消确认。

请参考：约束（P60）、错误（P82）、包容性（P104）、错误进一错误出（P112）。

![](/SCR-20240525-hfgh.png)

使用确认策略的常见案例包括：输入密码两次，以确认拼字正确；按下动作键（送出）确认执行动作的意图，并有选项可以取消即将执行的确认；要打开阀
门之前，先要把锁打开；需要转动两把特制钥匙，才能完成发射程序。![](/SCR-20240525-hfic.png)
![](/SCR-20240525-hfkj.png)