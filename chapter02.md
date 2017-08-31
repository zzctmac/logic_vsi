# 第2章：真值函数——抑或不是？

无论关于有效性的规则是否固化到我们大脑里，我们对于有效性或各种推断都有很强的直觉。比如，以下推断是有效的是没有多少争议的：“她是女人且是银行家；因此她是银行家”。以下推断是无效的：“他是木匠；因此他是木匠且打棒球”。

但我们的直觉有时会让我们陷入麻烦。你怎么看下面这个推断？两个前提出现在横线上，结论在横线下。


$$
\dfrac{女王富有。女王不富有。}{猪会飞。}
$$


它看上去当然不是有效的。女王的财富——无论多少——似乎都和猪的飞行能力无关。

但你认为以下两个推断怎么样？


$$
\dfrac{女王富有。}{女王富有或猪会飞。}
$$



$$
\dfrac{女王富有或猪会飞。女王不富有。}{猪会飞}
$$


第一个推断似乎是有效的。考虑它的结论。逻辑学家将这样的语句称为**析取式**（disjunction），将“或”两边的子句称为**析取项**（disjuncts）。那么，一个析取式怎样为真呢？只要其中一个析取项为真即可。因此对于第一个推断，在任何前提为真的情形，结论也为真。第二个推断似乎也是有效的。如果两个论断中的一个或另一个为真，且其中一个不为真，那么另一个必定为真。

现在的麻烦是，把两个明显有效的推断放在一起，我们就得到了明显无效的推断，像这样：


$$
\dfrac{女王富有\qquad\qquad\qquad}{\dfrac{女王富有或猪会飞。女王不富有。}{猪会飞。}}
$$


这不会是对的。将两个有效的推断以这种方式连接起来不会得到一个无效的推断。如果在某个情形下所有前提为真，那么它们的所有结论也为真，由这些结论推得的结论也为真，如此下去，直到我们得到最终的结论。问题出在哪儿呢？

为了给这个问题一个正统的回答，让我们更详细地考察一下。首先，我们把语句“猪会飞”写作 $$p$$，把语句“女王富有”写作 $$q$$，这让事情更加紧凑，但不止于此：如果你思考一下，就会发现在这个例子中使用什么具体语句是无关紧要的，我完全可以使用任意两个语句来构造这种形式的推断，因此我们可以忽略其内容，这正是我们将语句记作单个字母时所做的。
