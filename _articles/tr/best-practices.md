---
lang: tr
title: Bakımcılar için En İyi Uygulamalar
description: Süreçleri belgelemekten topluluğunuzu güçlendirmeye kadar açık kaynak bakımcısı olarak hayatınızı kolaylaştıracak unsurlar.
class: iyi-uygulamalar
order: 5
image: /assets/images/cards/best-practices.png
related:
  - metrics
  - leadership
---

## Bakımcı olmak ne anlama geliyor?

Eğer açık kaynak bir projenin bakımcılığını üstleniyorsanız, kodlama yapmaktan çok sorunlara yanıt vermeye zaman harcadığınızı farketmiş olabilirsiniz.

Bir projenin erken safhalarında yeni fikirleri dener ve istediğiniz doğrultuda kararlar alırsınız. Projenizin tanınırlığı arttıkça, kullanıcılarınız ve katılımcılarınız ile daha sık çalışmaya başlayacaksınız.

Bir projenin bakımını yapmak sadece kod yazmaktan fazlasıdır. Ortaya çıkan diğer işler genelde beklenmedik olmakla beraber projenin büyümesi için kod yazmak kadar önemlidir. Süreçleri belgeye dökmekten, topluluğunuzu yetkilendirmeye kadar hayatınızı kolaylaştıracak bir kaç yöntemi sizin için derledik.

## Süreçlerinizi belgeleyin

Her şeyi yazmak bir bakımcı olarak yapabileceğiniz en önemli işlerden biridir.

Belgeleme sadece kendi düşüncelerinizi netleştirmekle kalmaz, diğerlerinin de sizin beklenti ve ihtiyaçlarınızı fazladan soru sormadan anlamasına yardımcı olur.

Yazmak, amacınıza uymayan şeylere hayır demeyi kolaylaştırır. Ayrıca diğerlerinin de size katılıp yardımcı olmasını kolaylaştırır. Projenizi en beklemediğiniz kişiler bile okuyor veya kullanıyor olabilir.

Tam paragraf yazılar yazmasanız bile, bir kaç madde başlığı eklemek hiç yazmamaktan iyidir.

Belgelemenizi güncel tutmaya özen gösterin. Bunu yapma imkanınız yoksa, eski belgeleri silin veya onun eski olduğunu belirtin ki katılımcılar da güncellenmesine yardımcı olsunlar.

### Projenizin amacını yazıya dökün

Projenizin hedeflerini yazarak başlayabilirsiniz. Hedeflerinizi BENİOKU belgenize ekleyebilir veya ayrı bir AMAÇ belgesi oluşturabilirsiniz. Proje yol haritası gibi kolaylık sağlayacak başka belgeleriniz varsa, onları da herkesin erişimine açabilirsiniz.

Net ve belgeli bir amaca sahip olmak odağınızdan şaşmamanızı ve diğerlerinin katkıları sonucunda "kapsam kaymasına" uğramamanızı sağlar.

Örneğin, @lord bir proje amacına sahip olmanın, hangi talepler üzerinde zaman harcaması gerektiğini anlamasını sağladığını belirtiyor. Yeni bir bakımcı olarak [Slate](https://github.com/lord/slate) için ilk özellik talebini aldığı zamanlarda projesinin kapsamı dışına çıktığından dolayı pişman olduğunu dile getiriyor.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/lord?s=180" class="pquote-avatar" alt="avatar">
  İşi elime yüzüme bulaştırdım. Tam bir çözüm bulmak için yetince çaba sarfetmedim. Keşke yarım yamalak bir çözüm yerine "Bunun için şuanda zamanım yok ama uzun vadeli olsa iyi olur listesine ekleyeceğim" deseydim.
  <p markdown="1" class="pquote-credit">
— @lord, ["Tips for new open source maintainers"](https://lord.io/blog/2014/oss-tips/)
  </p>
</aside>

### Beklentilerinizi açıkça ortaya koyun

Kuralları yazıya dökmek oldukça can sıkıcı olabilir. Bazen diğerlerinin davranışlarını yönetmeye çalıştığınızı veya tüm eğlenceyi ortadan kaldırdığınızı düşünebilirsiniz.

Fakat yazılı oldukları ve adil şekilde uygulandıkları sürece iyi kurallar bakımcıların işlerini kolaylaştırırlar. Kurallar sizi istemediğiniz işleri yapmaya süreklenmekten alıkoyar.

Projenize denk gelen birçok kişi sizi veya içinde bulunduğunuz durumu bilmeyecektir. Eğer projeniz onların sıklıkla kullandıkları ve ihtiyaç duydukları bir konumda ise sizin bu iş için para aldığınızı varsayabilirler. Belki de geçmişte projeye çok zaman ayırmışsınızdır ama şimdi yeni bir iş veya aile bireyi ile meşgulsünüzdür.

Bunların hepsi gayet doğaldır! Sadece diğerlerinin durumunuzu bilmesini sağlayın.

Eğer projenizin bakımını yarı zamanlı veya tamamen gönüllü olarak sürdürüyorsanız, ayırabileceğiniz zaman konusunda dürüst olun. Bu, projenin ne kadar zamana ihtiyacı olduğunu düşündüğünüz veya başkalarınız sizden ne kadar zaman harcamanızı istediğiyle aynı şey değildir.

Yazmaya değer birkaç kuralı şöyle sıralayabiliriz:

* Bir katkının nasıl incelendiği ve kabul edildiği (_Testlere mi ihtiyaçları var? Veya bir sorun şablonuna?_)
* Kabul edeceğiniz katkıların türleri (_Kodunuzun sadece bir parçası için mi yardım istiyorsunuz?_)
* Takibe devam için uygun zamanın ne olduğu (_örneğin, "Bakımcılardan 7 gün içerisinde yanıt alacaksınız. Eğer bu süre içerisinde yanıt almadıysanız, başlığa ping atabilirsiniz."_)
* Projeye ne kadar zaman ayırdığınız (_örneğin, "Bu proje üzerinde haftada sadece 5 saat civarı çalışıyoruz."_)

[Jekyll](https://github.com/jekyll/jekyll/tree/master/docs), [CocoaPods](https://github.com/CocoaPods/CocoaPods/wiki/Communication-&-Design-Rules), ve [Homebrew](https://github.com/Homebrew/brew/blob/bbed7246bc5c5b7acb8c1d427d10b43e090dfd39/docs/Maintainers-Avoiding-Burnout.md) bakımcı ve katılımcılara yönelik temel kuralları olan projelerden bazılarıdır.

### İletişimi kamuya açık tutun

Etkileşimlerinizi de belgelemeyi unutmayın. Projenize ilişkin iletişimi mümkün olduğunca kamuya açık tutun. Eğer birisi özellik talep etmek veya destek istemek için sizinle şahsen iletişime geçerse, onları eposta listesi veya sorun izleme başlıkları gibi herkese açık bir iletişim kanalına yönlendirin.

Diğer bakımcılar ile buluşur veya şahsen büyük bir değişik yapma kararı alırsanız, bu görüşme ve kararları da kısa notlar şeklinde bile olsa belgeye dökerek kamu ile paylaşın.

Bu sayede, topluluğunuza katılan herkes projede yıllardır bulunanlar ile aynı bilgiye erişebilirler.

## Hayır demeyi öğrenin

Yazılacakları yazdınız. Herkes bu belgeri okusa çok iyi olurdu ama gerçekte bu bilginin var olduğunu diğerlerine hatırlatmak zorundasınız.

Elbette herşeyin yazıya dökülmüş olması, kuralları uygulamak gerektiğinde durumun kişisel boyuta düşmesini engeller.

Hayır demek hoş olmayabilir ama _"Katkınız bu projenin kıstaslarına uymamaktadır"_ demek _"Senin katkını beğenmedim"_ demekten daha az kişiseldir.

Hayır demek bir bakımcının sık ihtiyaç duyacağı bir iştir: özellik istemleri kapsama uymayabilir, birisi konuşmayı alakasız yerlere çekiyor olabilir veya ihtiyaç duyulmayan işler sunuluyor olabilir.

### İletişimi iyi niyet içerisinde sürdürün

One of the most important places you'll practice saying no is on your issue and pull request queue. As a project maintainer, you'll inevitably receive suggestions that you don't want to accept.

Maybe the contribution changes your project's scope or doesn't match your vision. Maybe the idea is good, but the implementation is poor.

Regardless of the reason, it is possible to tactfully handle contributions that don't meet your project's standards.

If you receive a contribution you don't want to accept, your first reaction might be to ignore it or pretend you didn't see it. Doing so could hurt the other person's feelings and even demotivate other potential contributors in your community.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/krausefx?s=180" class="pquote-avatar" alt="avatar">
  The key to handle support for large-scale open source projects is to keep issues moving. Try to avoid having issues stall. If you're an iOS developer you know how frustrating it can be to submit radars. You might hear back 2 years later, and are told to try again with the latest version of iOS.
  <p markdown="1" class="pquote-credit">
— @KrauseFx, ["Scaling open source communities"](https://krausefx.com/blog/scaling-open-source-communities)
  </p>
</aside>

Don't leave an unwanted contribution open because you feel guilty or want to be nice. Over time, your unanswered issues and PRs will make working on your project feel that much more stressful and intimidating.

It's better to immediately close the contributions you know you don't want to accept. If your project already suffers from a large backlog, @steveklabnik has suggestions for [how to triage issues efficiently](https://words.steveklabnik.com/how-to-be-an-open-source-gardener).

Secondly, ignoring contributions sends a negative signal to your community. Contributing to a project can be intimidating, especially if it's someone's first time. Even if you don't accept their contribution, acknowledge the person behind it and thank them for their interest. It's a big compliment!

If you don't want to accept a contribution:

* **Thank them** for their contribution
* **Explain why it doesn't fit** into the scope of the project, and offer clear suggestions for improvement, if you're able. Be kind, but firm.
* **Link to relevant documentation**, if you have it. If you notice repeated requests for things you don't want to accept, add them into your documentation to avoid repeating yourself.
* **Close the request**

You shouldn't need more than 1-2 sentences to respond. For example, when a user of [celery](https://github.com/celery/celery/) reported a Windows-related error, @berkerpeksag [responded with](https://github.com/celery/celery/issues/3383):

![Celery screenshot](/assets/images/best-practices/celery.png)

If the thought of saying no terrifies you, you're not alone. As @jessfraz [put it](https://blog.jessfraz.com/post/the-art-of-closing/):

> I've talked to maintainers from several different open source projects, Mesos, Kubernetes, Chromium, and they all agree one of the hardest parts of being a maintainer is saying "No" to patches you don't want.

Don't feel guilty about not wanting to accept someone's contribution. The first rule of open source, [according to](https://twitter.com/solomonstre/status/715277134978113536) @shykes: _"No is temporary, yes is forever."_ While empathizing with another person's enthusiasm is a good thing, rejecting a contribution is not the same as rejecting the person behind it.

Ultimately, if a contribution isn't good enough, you're under no obligation to accept it. Be kind and responsive when people contribute to your project, but only accept changes that you truly believe will make your project better. The more often you practice saying no, the easier it becomes. Promise.

### Önetkin olun

To reduce the volume of unwanted contributions in the first place, explain your project's process for submitting and accepting contributions in your contributing guide.

If you're receiving too many low-quality contributions, require that contributors do a bit of work beforehand, for example:

* Fill out a issue or PR template/checklist
* Open an issue before submitting a PR

If they don't follow your rules, close the issue immediately and point to your documentation.

While this approach may feel unkind at first, being proactive is actually good for both parties. It reduces the chance that someone will put in many wasted hours of work into a pull request that you aren't going to accept. And it makes your workload easier to manage.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/mikemcquaid?s=180" class="pquote-avatar" alt="avatar">
  Ideally, explain to them and in a CONTRIBUTING.md file how they can get a better indication in the future on what would or would not be accepted before they begin the work.
  <p markdown="1" class="pquote-credit">
— @MikeMcQuaid, ["Kindly Closing Pull Requests"](https://github.com/blog/2124-kindly-closing-pull-requests)
  </p>
</aside>

Sometimes, when you say no, your potential contributor may get upset or criticize your decision. If their behavior becomes hostile, [take steps to defuse the situation](https://github.com/jonschlinkert/maintainers-guide-to-staying-positive#action-items) or even remove them from your community, if they're not willing to collaborate constructively.

### Yol gösterici olun

Maybe someone in your community regularly submits contributions that don't meet your project's standards. It can be frustrating for both parties to repeatedly go through rejections.

If you see that someone is enthusiastic about your project, but needs a bit of polish, be patient. Explain clearly in each situation why their contributions don't meet the expectations of the project. Try pointing them to an easier or less ambiguous task, like an issue marked _"good first issue,"_ to get their feet wet. If you have time, consider mentoring them through their first contribution, or find someone else in your community who might be willing to mentor them.

## Topluluğunu yetkilendirin

You don't have to do everything yourself. Your project's community exists for a reason! Even if you don't yet have an active contributor community, if you have a lot of users, put them to work.

### İş yükünü paylaşın

If you're looking for others to pitch in, start by asking around.

When you see new contributors making repeated contributions, recognize their work by offering more responsibility. Document how others can grow into leadership roles if they wish.

Encouraging others to [share ownership of the project](../building-community/#share-ownership-of-your-project) can greatly reduce your own workload, as @lmccart discovered on her project, [p5.js](https://github.com/processing/p5.js).

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/lmccart?s=180" class="pquote-avatar" alt="avatar">
  I’d been saying, "Yeah, anyone can be involved, you don’t have to have a lot of coding expertise [...]." We had people sign up to come [to an event] and that’s when I was really wondering: is this true, what I’ve been saying? There are gonna be 40 people who show up, and it’s not like I can sit with each of them...But people came together, and it just sort of worked. As soon as one person got it, they could teach their neighbor.
  <p markdown="1" class="pquote-credit">
—  @lmccart, ["What Does "Open Source" Even Mean? p5.js Edition"](https://medium.com/@kenjagan/what-does-open-source-even-mean-p5-js-edition-98c02d354b39)
  </p>
</aside>

If you need to step away from your project, either on hiatus or permanently, there's no shame in asking someone else to take over for you.

If other people are enthusiastic about its direction, give them commit access or formally hand over control to someone else. If someone forked your project and is actively maintaining it elsewhere, consider linking to the fork from your original project. It's great that so many people want your project to live on!

@progrium [found that](https://progrium.com/blog/2015/12/04/leadership-guilt-and-pull-requests/) documenting the vision for his project, [Dokku](https://github.com/dokku/dokku), helped those goals live on even after he stepped away from the project:

> I wrote a wiki page describing what I wanted and why I wanted it. For some reason it came as a surprise to me that the maintainers started moving the project in that direction! Did it happen exactly how I'd do it? Not always. But it still brought the project closer to what I wrote down.

### Diğerlerinin ihtiyaç duyduğu çözümleri yaratmalarına izin verin

If a potential contributor has a different opinion on what your project should do, you may want to gently encourage them to work on their own fork.

Forking a project doesn't have to be a bad thing. Being able to copy and modify projects is one of the best things about open source. Encouraging your community members to work on their own fork can provide the creative outlet they need, without conflicting with your project's vision.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/geerlingguy?s=180" class="pquote-avatar" alt="avatar">
  I cater to the 80% use case. If you are one of the unicorns, please fork my work. I won't get offended! My public projects are almost always meant to solve the most common problems; I try to make it easy to go deeper by either forking my work or extending it.
  <p markdown="1" class="pquote-credit">
— @geerlingguy, ["Why I Close PRs"](https://www.jeffgeerling.com/blog/2016/why-i-close-prs-oss-project-maintainer-notes)
  </p>
</aside>

The same applies to a user who really wants a solution that you simply don't have the bandwidth to build. Offering APIs and customization hooks can help others meet their own needs, without having to modify the source directly. @orta [found that](https://artsy.github.io/blog/2016/07/03/handling-big-projects/) encouraging plugins for CocoaPods led to "some of the most interesting ideas":

> It's almost inevitable that once a project becomes big, maintainers have to become a lot more conservative about how they introduce new code. You become good at saying "no", but a lot of people have legitimate needs. So, instead you end up converting your tool into a platform.

## Robotlardan faydalanın

Just as there are tasks that other people can help you with, there are also tasks that no human should ever have to do. Robots are your friend. Use them to make your life as a maintainer easier.

### Kodunuzun kalitesini arttırmak için testleri ve diğer kontrolleri talep edin

One of the most important ways you can automate your project is by adding tests.

Tests help contributors feel confident that they won't break anything. They also make it easier for you to review and accept contributions quickly. The more responsive you are, the more engaged your community can be.

Set up automatic tests that will run on all incoming contributions, and ensure that your tests can easily be run locally by contributors. Require that all code contributions pass your tests before they can be submitted. You'll help set a minimum standard of quality for all submissions. [Required status checks](https://help.github.com/articles/about-required-status-checks/) on GitHub can help ensure no change gets merged without your tests passing.

If you add tests, make sure to explain how they work in your CONTRIBUTING file.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/edunham?s=180" class="pquote-avatar" alt="avatar">
  I believe that tests are necessary for all code that people work on. If the code was fully and perfectly correct, it wouldn't need changes – we only write code when something is wrong, whether that's "It crashes" or "It lacks such-and-such a feature". And regardless of the changes you're making, tests are essential for catching any regressions you might accidentally introduce.
  <p markdown="1" class="pquote-credit">
— @edunham, ["Rust's Community Automation"](https://edunham.net/2016/09/27/rust_s_community_automation.html)
  </p>
</aside>

### Basit bakım görevlerini otomatikleştirmek için araçları kullanın

The good news about maintaining a popular project is that other maintainers have probably faced similar issues and built a solution for it.

There are a [variety of tools available](https://github.com/showcases/tools-for-open-source) to help automate some aspects of maintenance work. A few examples:

* [semantic-release](https://github.com/semantic-release/semantic-release) automates your releases
* [mention-bot](https://github.com/facebook/mention-bot) mentions potential reviewers for pull requests
* [Danger](https://github.com/danger/danger) helps automate code review

For bug reports and other common contributions, GitHub has [Issue Templates and Pull Request Templates](https://github.com/blog/2111-issue-and-pull-request-templates), which you can create to streamline the communication you receive. @TalAter made a [Choose Your Own Adventure guide](https://www.talater.com/open-source-templates/#/) to help you write your issue and PR templates.

To manage your email notifications, you can set up [email filters](https://github.com/blog/2203-email-updates-about-your-own-activity) to organize by priority.

If you want to get a little more advanced, style guides and linters can standardize project contributions and make them easier to review and accept.

However, if your standards are too complicated, they can increase the barriers to contribution. Make sure you're only adding enough rules to make everyone's lives easier.

If you're not sure which tools to use, look at what other popular projects do, especially those in your ecosystem. For example, what does the contribution process look like for other Node modules? Using similar tools and approaches will also make your process more familiar to your target contributors.

## Mola vermek doğaldır

Open source work once brought you joy. Maybe now it's starting to make you feel avoidant or guilty.

Perhaps you're feeling overwhelmed or a growing sense of dread when you think about your projects. And meanwhile, the issues and pull requests pile up.

Burnout is a real and pervasive issue in open source work, especially among maintainers. As a maintainer, your happiness is a non-negotiable requirement for the survival of any open source project.

Although it should go without saying, take a break! You shouldn't have to wait until you feel burned out to take a vacation. @brettcannon, a Python core developer, decided to take [a month-long vacation](https://snarky.ca/why-i-took-october-off-from-oss-volunteering/) after 14 years of volunteer OSS work.

Just like any other type of work, taking regular breaks will keep you refreshed, happy, and excited about your work.

<aside markdown="1" class="pquote">
  <img src="https://avatars.githubusercontent.com/danielbachhuber?s=180" class="pquote-avatar" alt="avatar">
  In maintaining WP-CLI, I've discovered I need to make myself happy first, and set clear boundaries on my involvement. The best balance I've found is 2-5 hours per week, as a part of my normal work schedule. This keeps my involvement a passion, and from feeling too much like work. Because I prioritize the issues I'm working on, I can make regular progress on what I think is most important.
  <p markdown="1" class="pquote-credit">
— @danielbachhuber, ["My condolences, you're now the maintainer of a popular open source project"](https://runcommand.io/2016/06/26/my-condolences-youre-now-the-maintainer-of-a-popular-open-source-project/)
  </p>
</aside>

Sometimes, it can be hard to take a break from open source work when it feels like everybody needs you. People may even try to make you feel guilty for stepping away.

Do your best to find support for your users and community while you're away from a project. If you can't find the support you need, take a break anyway. Be sure to communicate when you're not available, so people aren't confused by your lack of responsiveness.

Taking breaks applies to more than just vacations, too. If you don't want to do open source work on weekends, or during work hours, communicate those expectations to others, so they know not to bother you.

## Her şeyden önce kendinize iyi bakın!

Maintaining a popular project requires different skills than the earlier stages of growth, but it's no less rewarding. As a maintainer, you'll practice leadership and personal skills on a level that few people get to experience. While it's not always easy to manage, setting clear boundaries and only taking on what you're comfortable with will help you stay happy, refreshed, and productive.
