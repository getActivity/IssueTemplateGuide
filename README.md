# issue 模板填写指南

* 项目地址：[Github](https://github.com/getActivity/IssueTemplateGuide)

## 常见疑问解答

#### 目录

* [提问题为什么一定要用 issue 来提](#提问题为什么一定要用-issue-来提)

* [为什么要严格按照 issue 模板填写问题](#为什么要严格按照-issue-模板填写问题)

* [要是在 issue 模板上面乱填会怎么样](#要是在-issue-模板上面乱填会怎么样)

* [bug issue 和疑惑 issue 的区别](#bug-issue-和疑惑-issue-的区别)

* [为什么不处理框架的个人使用问题](#为什么不处理框架的个人使用问题)

* [为什么不处理个人遇到的技术问题](#为什么不处理个人遇到的技术问题)

* [最后带给大家的一段话](#最后带给大家的一段话)

#### 提问题为什么一定要用 issue 来提

* 之所以要求大家不要通过 QQ 和微信和我反馈，而是到 Github 提问题的原因是，我和某个人在通讯软件上面的聊天，别人是看不到的，对于别人来讲是没有任何痕迹的，这样就会导致一个问题，今天张三问这个问题，我就得回答一次，明天李四问这个问题，我又得回答一次，后天王五问这个问题，我又又得回答一次，一万个人问一次，我就得回答一万遍，但是用 Github issue 就不一样了，issue 模板已经写了是否有人提过类似的问题，大大有效避免同一个问题被问 N 遍，我也能避免成为复读机。

* 当然真实的情况是，如果我不那么做，今天可能不止有张三一个人来问，而是十几个人甚至几十个人来问，如果换做你是开源作者，那你会怎么做？

#### 为什么要严格按照 issue 模板填写问题

* 主要的原因有以下几个：

    * 提问题的人随便提，而开源作者却要十分认真对待这些问题，这对于开源作者来讲是不公平的，因为你的随意可能会给开源作者造成不必要的工作量。

    * 提问题的时候不看文档是对开源作者的不尊重，我写文档是为了避免成为一台复读机，而你不看文档来问，那么我又变成了复读机，那么写文档的意义又在哪里？

    * 提问题的时候注意看之前的人有没有人提过了，有的话也尽量别再提，避免我再次成为复读机，直接在原帖下面回复，这样我也能看到，你也不需要重新提 issue。

    * 提 Bug 的时候，不写出现问题的框架版本，不写出现手机信息，不写复现步骤，你确定这是在提 issue，而不是在找我算命？

    * 我并不是立马就能回复 issue 问题，需要先忙完手头的工作才可以，同理大家回复我也是一样，需要一定的时间成本，所以早期能提供的信息尽量提供，不要等问到了再说，那样效率可能会更慢。

#### 要是在 issue 模板上面乱填会怎么样

* 会被关闭，提 issue 的时候，已经十分显眼地提示了，乱填 issue 的一概不受理，因为乱填的 issue 会给我造成很多困扰，例如这个问题前面已经有好几个人问了，我前面已经解决过很多遍了，然后你又再问一遍，这种情况下我就得重复回答，在开始做开源的时候，我都会回答，但是时间久了发现，我一直在回答重复且没有意义的问题，那么问题到底出在哪里了呢？到底是谁的错？经过不断反思，最终发现是我自己的问题，之前一直没有要求提 issue 的人一定要看过文档、看看是否有人提过相同的 issue 等等，这变相给了别人乱写的 issue 的权利，给别人造成了一种错觉，反正你也没说，我怎么方便怎么来，所以这个是之前我的错误，没有要求大家那样做，但是现在有了，我在 issue 的填写上面做一些限制，并且强制要求每一个提 issue 的人遵守，不遵守的人问题将无法得到解决，如果不遵守规则的人问题都能得到解决，这将是对遵守规则的人最大的不公平，规则也将成为一张废纸。

#### bug issue 和疑惑 issue 的区别

* 具体的区别如下：运行代码遇到一切异常都可以算 Bug，比如崩溃闪退、应用程序无响应、UI 错乱、数据显示有问题，原本要执行逻辑没有执行，原本不需要执行的逻辑却执行了等等这些问题都能算 Bug，简单概括就是代码运行层面遇到的一些异常，然后只要是 Bug，无论是系统的还是应用的，都是需要提 Bug 单，而不是提疑问单或者建议单，疑问单开放出来主要是为了解答一些非 Bug 级别问题的，比如：框架为什么不转成 AndroidX？框架里面的那句代码这样写会不会有什么问题？遇到一个奇葩的需求框架满足不了该怎么办？文档那样写是不是有问题？代码注释那样写是不是导致误解/错误？等等这种问题就可以提疑问 issue 单。

* 还有一种情况，如果不确定问题到底是不是 Bug？那么大概率是 Bug 了，请按照 Bug issue 模板进行填写。

* 由于 Bug issue 模板需要填写的内容较多，而疑惑 issue 需要填写的内容比较少，有的人为了图省事，把 Bug 的问题使用疑惑 issue 模板填写，这种方式是错误的，在我这里是会被直接打回的，需要大家额外注意。

#### 为什么不处理框架的个人使用问题

* 因为能提这类问题的人，一般连问题的原因是什么都搞不清楚就来问，刚开始做开源的时候我会照收不误，但是现在不一样的，现在要求每一个人提问题的人，必须要求明确问题的原因，而不是交给我去帮忙排查，具体这样做的主要原因有如下：

    * 大多数的个人使用问题，都可以通过查看文档和代码注释来解决，但是大多数时候人性是懒惰的

    * 排查问题是一个耗时操作，一般情况下没有两三个小时很难定位到问题，但是开源作者一个人身单力薄

    * 从金钱成本上看：不得不要面对一个非常残酷和现实的问题，同样是排查问题，我没有办法从你那里挣到钱，但是你可以从老板那里挣到钱，你完全可以把今天排查的问题写到工作汇报上面，算做工作内容的一部分，但是我不行。

  * 从时间成本上看：假设一天有 6 个人，每个人各有 1 个问题需要我协助排查，那么我总共需要花费 3 * 6 = 18 小时，除去不挣钱不说，剩下 6 小时连睡觉都不够，所以这样做是不现实的，如果把 6 个问题派发给每个人去排查，那么他们只需要花费 2 ~ 3 小时即可解决问题，另外这样做并不意味着我一点时间都不需要花，有些问题排查出来的结果是个人的问题，有些问题排查出来的结果是框架的问题，最终确定是框架那部分的问题还需要我去处理，处理问题也需要消耗大量的时间，只不过提前筛掉了一些原本就不属于我的问题。

* 所以大家提问题的时候要先明确问题，并不是我不愿意给大家解决问题，而是一个人时间和精力实在有限，开源只是我生活中的一部分，轮子哥也要工作、吃饭、睡觉、休息，当每天时间不够用的时候，我就不得不做取舍。

* 所以需要大家先确认好问题是不是属于框架的，再找我处理，如果确定是框架的问题，我会做处理的，这点大家不必担心。

#### 为什么不处理个人遇到的技术问题

* 我觉得原因有如下几个：

    * 不挣钱：因为开源不挣钱，所以提供不了服务，不知道大家有没有注意到，上网买东西去找店家都有客服接待，打 10000、10010、10086 都有客服接待，这些服务本质上来源于你要消费或者已经消费，为他们产生了收益，包括找劳动局找税务局等等都有人接待，并且还不需要花钱，这是因为你发工资前扣了税，国家要把交的税给一部分来养活这些单位，或许每一种服务已经在暗中标好了价格。开源挣不到钱，会导致我请不起人，这样也将意味着任何事情都需要我亲力亲为，什么事都要自己做将意味着我的时间是远远不够的，和框架有关系的问题，需要我进行处理，和框架没有关系的问题，我完全可以拒绝回答的。

    * 人性原因：如果叫一声大佬，就会有大佬放下手头的事情来服务你，那真的是太美好了，但是现实情况是，大佬们也有自己的事情要做，也要打工生存，没有办法放下手头的砖，然后去给别人搬砖，如果可以做到，那么在遇到难题的时候，我也想喊别人一声大佬，自己解决问题多麻烦，把问题丢给别人永远是最轻松的，最好躺着就能把钱挣了。大家其实都那么想，那么谁来当这个大佬呢？有人可能会说了，这不是妥妥冤大头吗？自己的事情不做跑去帮别人，结果帮完连句谢谢都没有，等下自己的事情还很可能搞砸了。我想和大家说的是，大佬们是人不是神，没有三头六臂，更没有分身的超能力，一天时间和大家一样只有 24 个小时，也要吃饭睡觉和拉屎（虽然用词不雅，但是话糙理不糙）。

* 有的人可能就会喷了，说得那么冠冕堂皇，你就是一个精致的利己主义者，枉费你还叫轮子哥，我呸，啥也不是。当你站在自己的角度思考问题的时候，想到的只有自己，当你能站在全局的角度思考问题的时候，才能明白我为什么那么做。如果有一天你成为了轮子哥，你也一定会那么做，因为真的没有别的选择，要么拒绝帮忙，要么被这些问题活活耗死。还有我并非完全是一个精致的利己主义者，如果是的话，大家也不会看到我开源的框架了，因为前面也讲过了开源其实是不挣钱的，我是一个现实的理想主义者，既要理想，又要面对现实，也或许是我的能力有限，只能做到这样了。

#### 最后带给大家的一段话

* 跟大家讲这些，主要是让大家知道我这样做的原因，当大家真正明白开源作者的难处和不易的时候，彼此相互理解的时候，我在开源这条道路才能走得更远，虽然知道在未来的某一天我的开源会停更，但是我会尽量坚持，陪着大家走到最后，我相信放弃并不难，但是坚持一定很酷。

#### 开源项目列表

* 安卓技术中台：[AndroidProject](https://github.com/getActivity/AndroidProject) ![](https://img.shields.io/github/stars/getActivity/AndroidProject.svg) ![](https://img.shields.io/github/forks/getActivity/AndroidProject.svg)

* 安卓技术中台 Kt 版：[AndroidProject-Kotlin](https://github.com/getActivity/AndroidProject-Kotlin) ![](https://img.shields.io/github/stars/getActivity/AndroidProject-Kotlin.svg) ![](https://img.shields.io/github/forks/getActivity/AndroidProject-Kotlin.svg)

* 权限框架：[XXPermissions](https://github.com/getActivity/XXPermissions) ![](https://img.shields.io/github/stars/getActivity/XXPermissions.svg) ![](https://img.shields.io/github/forks/getActivity/XXPermissions.svg)

* 吐司框架：[Toaster](https://github.com/getActivity/Toaster) ![](https://img.shields.io/github/stars/getActivity/Toaster.svg) ![](https://img.shields.io/github/forks/getActivity/Toaster.svg)

* 网络框架：[EasyHttp](https://github.com/getActivity/EasyHttp) ![](https://img.shields.io/github/stars/getActivity/EasyHttp.svg) ![](https://img.shields.io/github/forks/getActivity/EasyHttp.svg)

* 标题栏框架：[TitleBar](https://github.com/getActivity/TitleBar) ![](https://img.shields.io/github/stars/getActivity/TitleBar.svg) ![](https://img.shields.io/github/forks/getActivity/TitleBar.svg)

* 悬浮窗框架：[XToast](https://github.com/getActivity/XToast) ![](https://img.shields.io/github/stars/getActivity/XToast.svg) ![](https://img.shields.io/github/forks/getActivity/XToast.svg)

* Shape 框架：[ShapeView](https://github.com/getActivity/ShapeView) ![](https://img.shields.io/github/stars/getActivity/ShapeView.svg) ![](https://img.shields.io/github/forks/getActivity/ShapeView.svg)

* 语种切换框架：[MultiLanguages](https://github.com/getActivity/MultiLanguages) ![](https://img.shields.io/github/stars/getActivity/MultiLanguages.svg) ![](https://img.shields.io/github/forks/getActivity/MultiLanguages.svg)

* Gson 解析容错：[GsonFactory](https://github.com/getActivity/GsonFactory) ![](https://img.shields.io/github/stars/getActivity/GsonFactory.svg) ![](https://img.shields.io/github/forks/getActivity/GsonFactory.svg)

* 日志查看框架：[Logcat](https://github.com/getActivity/Logcat) ![](https://img.shields.io/github/stars/getActivity/Logcat.svg) ![](https://img.shields.io/github/forks/getActivity/Logcat.svg)

* Android 版本适配：[AndroidVersionAdapter](https://github.com/getActivity/AndroidVersionAdapter) ![](https://img.shields.io/github/stars/getActivity/AndroidVersionAdapter.svg) ![](https://img.shields.io/github/forks/getActivity/AndroidVersionAdapter.svg)

* Android 代码规范：[AndroidCodeStandard](https://github.com/getActivity/AndroidCodeStandard) ![](https://img.shields.io/github/stars/getActivity/AndroidCodeStandard.svg) ![](https://img.shields.io/github/forks/getActivity/AndroidCodeStandard.svg)

* Android 资源大汇总：[AndroidIndex](https://github.com/getActivity/AndroidIndex) ![](https://img.shields.io/github/stars/getActivity/AndroidIndex.svg) ![](https://img.shields.io/github/forks/getActivity/AndroidIndex.svg)

* Android 开源排行榜：[AndroidGithubBoss](https://github.com/getActivity/AndroidGithubBoss) ![](https://img.shields.io/github/stars/getActivity/AndroidGithubBoss.svg) ![](https://img.shields.io/github/forks/getActivity/AndroidGithubBoss.svg)

* Studio 精品插件：[StudioPlugins](https://github.com/getActivity/StudioPlugins) ![](https://img.shields.io/github/stars/getActivity/StudioPlugins.svg) ![](https://img.shields.io/github/forks/getActivity/StudioPlugins.svg)

* 表情包大集合：[EmojiPackage](https://github.com/getActivity/EmojiPackage) ![](https://img.shields.io/github/stars/getActivity/EmojiPackage.svg) ![](https://img.shields.io/github/forks/getActivity/EmojiPackage.svg)

* AI 资源大汇总：[AiIndex](https://github.com/getActivity/AiIndex) ![](https://img.shields.io/github/stars/getActivity/AiIndex.svg) ![](https://img.shields.io/github/forks/getActivity/AiIndex.svg)

* 省市区 Json 数据：[ProvinceJson](https://github.com/getActivity/ProvinceJson) ![](https://img.shields.io/github/stars/getActivity/ProvinceJson.svg) ![](https://img.shields.io/github/forks/getActivity/ProvinceJson.svg)

* Markdown 语法文档：[MarkdownDoc](https://github.com/getActivity/MarkdownDoc) ![](https://img.shields.io/github/stars/getActivity/MarkdownDoc.svg) ![](https://img.shields.io/github/forks/getActivity/MarkdownDoc.svg)

#### 微信公众号：Android轮子哥

![](https://raw.githubusercontent.com/getActivity/Donate/master/picture/official_ccount.png)

#### Android 技术 Q 群：10047167

#### 如果您觉得我的开源库帮你节省了大量的开发时间，请扫描下方的二维码随意打赏，要是能打赏个 10.24 :monkey_face:就太:thumbsup:了。您的支持将鼓励我继续创作:octocat:

![](https://raw.githubusercontent.com/getActivity/Donate/master/picture/pay_ali.png) ![](https://raw.githubusercontent.com/getActivity/Donate/master/picture/pay_wechat.png)

#### [点击查看捐赠列表](https://github.com/getActivity/Donate)

## License

```text
Copyright 2023 Huang JinQun

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```