<template>
  <div class="px-6 pb-24 mt-2 md:pb-32 md:px-12 lg:px-16">
    <div class="flex flex-col items-center justify-center max-w-6xl mx-auto">
      <!-- 头像与徽章 -->
      <div class="relative w-full mx-auto">
        <!-- 头像 -->
        <div class="relative py-2 h-52">
          <div
            class="absolute w-48 h-48 mx-auto rounded-full shadow-[0px_0px_3px#147eae] dark:shadow-[0px_0px_3px#9ba0a9] top-1/2 avatar-ping left-1/2">
          </div>
          <img class="block w-48 h-48 mx-auto rounded-full" src="/66.jpg" alt="avatar" />
        </div>
        <!-- Right-tags -->
        <p style="top: 32%"
          class="tag-bounce hidden sm:block sm:left-[69%] md:left-[66%] lg:left-[63%] xl:left-[60%] absolute px-3 py-0.5 text-sm font-bold rounded-full shadow-[0px_0px_1px_1px#eee]">
          🎵 sofity
        </p>
        <p style="top: 50%"
          class="tag-bounce hidden sm:block sm:left-[69%] md:left-[66%] lg:left-[63%] xl:left-[60%] absolute px-3 py-0.5 text-sm font-bold rounded-full shadow-[0px_0px_1px_1px#eee]">
          🌙 Netflix
        </p>
        <!-- Left-tags -->
        <p style="top: 32%"
          class="tag-bounce hidden sm:block sm:left-[8%] md:left-[13%] lg:left-[21%] xl:left-[27%] absolute px-3 py-0.5 text-sm font-bold rounded-full shadow-[0px_0px_1px_1px#eee]">
          🌟 孤独的程序员
        </p>
        <p style="top: 50%"
          class="tag-bounce hidden sm:block sm:left-[8%] md:left-[13%] lg:left-[21%] xl:left-[27%] absolute px-3 py-0.5 text-sm font-bold rounded-full shadow-[0px_0px_1px_1px#eee]">
          ✨Coding with dream
        </p>
      </div>
      <!-- 概述与箴言 -->
      <div class="flex flex-col w-full mt-4">
        <div class="flex flex-col justify-between gap-5 md:gap-0 md:flex-row">
          <!-- 概述 -->
          <div
            class="dark:from-sky-700 dark:to-teal-600 dark:border-slate-900 w-full flex flex-col justify-center rounded-xl border py-4 px-8 text-white md:w-[59%] bg-gradient-to-r from-sky-400 to-teal-400">
            <p class="text-lg text-slate-50">
              你好，我是Along，来自中国，很高兴认识你 👋
            </p>
            <h1 class="text-xl font-bold xl:text-3xl lg:break-normal lg:break-words">
              🌟 Dream to be a full-stack developer.
            </h1>
            <p class="text-slate-100">后端开发 / 主机游戏爱好者 / 音乐发烧友 / 撸铁小白 </p>
          </div>
          <!-- 箴言 -->
          <div
            class="bg-stripe dark:border-slate-900 dark:bg-slate-800 md:w-[39%] w-full rounded-xl border p-4 bg-slate-50">
            <p class="text-[12px]">💬 Motto</p>
            <div>
              <h1 class="text-2xl leading-9">
                <span class="hidden font-bold text-teal-400 md:inline-block">💬 A blog is not just a website.&nbsp;
                </span>
                <span class="hidden lg:inline-block">It's a voice, &nbsp;</span>
              </h1>
              <h1 class="font-serif text-3xl tracking-widest md:text-2xl lg:text-3xl">
                <span class="font-bold text-sky-500">a conversation</span> and a
                community.
              </h1>
              <h1 class="text-2xl leading-9 md:text-3xl">
                <span class="inline-block font-bold text-teal-400 md:hidden">Blogs are used to record study and
                  life.&nbsp;
                </span>
                <span class="inline-block lg:hidden">Is Everywhere</span>
              </h1>
            </div>
          </div>
        </div>
      </div>
      <!-- 简介与技术栈 -->
      <div class="flex flex-col justify-between w-full gap-5 mt-4 md:gap-0 md:flex-row">
        <!-- 简介 -->
        <div
          class="bg-stripe w-full md:w-[35%] bg-slate-50 border dark:bg-slate-800 dark:border-slate-900 p-4 rounded-xl">
          <p class="text-[12px]">💡 I am a software engineering student.</p>
          <div class="mt-2">
            <h1 class="text-xl">😺Love coding and open source.</h1>
            <h1 class="text-xl">🎂Generation Z born in China.</h1>
            <h1 class="text-xl lg:text-xl md:text-base">🔥🌱</h1>
            <p></p>
          </div>
        </div>
        <!-- 技术栈 -->
        <div class="w-full md:w-[62%] dark:border-slate-900 border dark:bg-slate-800 bg-slate-50 p-4 rounded-xl">
          <p class="text-[12px]">技术栈</p>
          <div class="mt-2 overflow-hidden">
            <!-- TODO:封装ICON组件,抽离背景颜色与svg地址 -->
            <div class="flex gap-4 w-fit icon-scroll">
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 rounded-lg bg-slate-200">
                <!-- java-->
                <img src="https://user-images.githubusercontent.com/25181517/117201156-9a724800-adec-11eb-9a9d-3cd0f67da4bc.png" alt="" />
              </div>
              <!--spring-->
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 rounded-lg bg-slate-200">
                <img src="https://user-images.githubusercontent.com/25181517/117201470-f6d56780-adec-11eb-8f7c-e70e376cfd07.png" alt="" />
              </div>
              <!-- redis-->
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 bg-slate-200 rounded-lg">
                <img class="rounded-lg" src="https://user-images.githubusercontent.com/25181517/182884894-d3fa6ee0-f2b4-4960-9961-64740f533f2a.png" alt="" />
              </div>
              <!--maven-->
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 bg-slate-200">
                <img class="rounded-lg" src="https://user-images.githubusercontent.com/25181517/117207242-07d5a700-adf4-11eb-975e-be04e62b984b.png" alt="" />
              </div>
              <div class="flex-shrink-0 w-20 h-20 p-4 bg-slate-200 rounded-lg">
                <!-- mysql-->
                <img src="https://user-images.githubusercontent.com/25181517/183896128-ec99105a-ec1a-4d85-b08b-1aa1620b2046.png" alt="" />
              </div>
              <!-- oracle-->
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 bg-slate-200 rounded-lg">
                <img class="rounded-lg" src="https://user-images.githubusercontent.com/25181517/117208736-bdedc080-adf5-11eb-912f-61c7d43705f6.png" alt="" />
              </div>
              <!-- mongodb-->
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 bg-slate-50">
                <img class="rounded-lg" src="https://user-images.githubusercontent.com/25181517/182884177-d48a8579-2cd0-447a-b9a6-ffc7cb02560e.png" alt="" />
              </div>
              <div class="flex-shrink-0 w-20 h-20 p-4 rounded-lg bg-slate-50">
                <!-- docker-->
                <img src="https://user-images.githubusercontent.com/25181517/117207330-263ba280-adf4-11eb-9b97-0ac5b40bc3be.png" alt="" />
              </div>

              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 rounded-lg bg-slate-50">
                <!-- k8s-->
                <img src="https://user-images.githubusercontent.com/25181517/182534006-037f08b5-8e7b-4e5f-96b6-5d2a5558fa85.png" alt="" />
              </div>
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 bg-slate-50">
                <img class="rounded-lg" src="https://user-images.githubusercontent.com/25181517/192108372-f71d70ac-7ae6-4c0d-8395-51d8870c2ef0.png" alt="" />
              </div>
              <!-- jeckins-->
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 rounded-lg bg-slate-50">
                <img class="rounded-lg" src="https://user-images.githubusercontent.com/25181517/179090274-733373ef-3b59-4f28-9ecb-244bea700932.png" alt="" />
              </div>
              <!-- 橙-->
              <div class="flex justify-center w-20 h-20 p-4 flex-shrink-0 rounded-lg bg-slate-50">
                <img class="rounded-lg" src="https://user-images.githubusercontent.com/25181517/182534182-c510199a-7a4d-4084-96e3-e3db2251bbce.png" alt="" />
              </div>
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 rounded-lg bg-slate-50">
                <img src="./img/vue.svg" alt="vue.js" />
              </div>
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 rounded-lg bg-slate-200">
                <!-- java-->
                <img src="https://user-images.githubusercontent.com/25181517/117201156-9a724800-adec-11eb-9a9d-3cd0f67da4bc.png" alt="" />
              </div>
              <!--spring-->
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 rounded-lg bg-slate-200">
                <img src="https://user-images.githubusercontent.com/25181517/117201470-f6d56780-adec-11eb-8f7c-e70e376cfd07.png" alt="" />
              </div>
              <!-- redis-->
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 bg-slate-200 rounded-lg">
                <img class="rounded-lg" src="https://user-images.githubusercontent.com/25181517/182884894-d3fa6ee0-f2b4-4960-9961-64740f533f2a.png" alt="" />
              </div>
              <!--maven-->
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 bg-slate-200">
                <img class="rounded-lg" src="https://user-images.githubusercontent.com/25181517/117207242-07d5a700-adf4-11eb-975e-be04e62b984b.png" alt="" />
              </div>
              <div class="flex-shrink-0 w-20 h-20 p-4 bg-slate-200 rounded-lg">
                <!-- mysql-->
                <img src="https://user-images.githubusercontent.com/25181517/183896128-ec99105a-ec1a-4d85-b08b-1aa1620b2046.png" alt="" />
              </div>
              <!-- oracle-->
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 bg-slate-200 rounded-lg">
                <img class="rounded-lg" src="https://user-images.githubusercontent.com/25181517/117208736-bdedc080-adf5-11eb-912f-61c7d43705f6.png" alt="" />
              </div>
              <!-- mongodb-->
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 bg-slate-50">
                <img class="rounded-lg" src="https://user-images.githubusercontent.com/25181517/182884177-d48a8579-2cd0-447a-b9a6-ffc7cb02560e.png" alt="" />
              </div>
              <div class="flex-shrink-0 w-20 h-20 p-4 rounded-lg bg-slate-50">
                <!-- docker-->
                <img src="https://user-images.githubusercontent.com/25181517/117207330-263ba280-adf4-11eb-9b97-0ac5b40bc3be.png" alt="" />
              </div>

              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 rounded-lg bg-slate-50">
                <!-- k8s-->
                <img src="https://user-images.githubusercontent.com/25181517/182534006-037f08b5-8e7b-4e5f-96b6-5d2a5558fa85.png" alt="" />
              </div>
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 bg-slate-50">
                <img class="rounded-lg" src="https://user-images.githubusercontent.com/25181517/192108372-f71d70ac-7ae6-4c0d-8395-51d8870c2ef0.png" alt="" />
              </div>
              <!-- jeckins-->
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 rounded-lg bg-slate-50">
                <img class="rounded-lg" src="https://user-images.githubusercontent.com/25181517/179090274-733373ef-3b59-4f28-9ecb-244bea700932.png" alt="" />
              </div>
              <!-- 橙-->
              <div class="flex justify-center w-20 h-20 p-4 flex-shrink-0 rounded-lg bg-slate-50">
                <img class="rounded-lg" src="https://user-images.githubusercontent.com/25181517/182534182-c510199a-7a4d-4084-96e3-e3db2251bbce.png" alt="" />
              </div>
              <div class="flex justify-center flex-shrink-0 w-20 h-20 p-4 rounded-lg bg-slate-50">
                <img src="./img/vue.svg" alt="vue.js" />
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- 图片与荣誉 -->
      <div class="flex flex-col justify-between w-full gap-5 mt-4 md:gap-0 md:flex-row">
        <!-- 图片 -->
        <div class="w-full md:w-[45%] honer-bg bg-center bg-no-repeat bg-cover rounded-xl h-52 sm:h-auto"></div>
        <!-- 荣誉 -->
        <div
          class="bg-stripe w-full md:w-[50%] bg-slate-50 border dark:bg-slate-800 dark:border-slate-900 p-4 rounded-xl">
          <p class="text-[12px]">🏆 Awards</p>
          <h1 class="mt-2 text-4xl font-bold text-yellow-400">追风赶月</h1>
          <div class="mt-4 md:text-base lg:text-xl">
            <p class="py-1 text-orange-400 font-semibold">
              🏅
              <a href="https://github.com/LofiSu/LofiSu/blob/main/My%20Honors%20and%20Awards.md" class="underline">My
                Honors and Awards</a>
            </p>
            <p class="py-1 text-red-600">
              🌟
              <span class="font-bold">Second prize in provincial software competition </span>
              <span class="italic"> of the 15th Blue Bridge Cup Competition</span>
            </p>

<!--            <p class="py-1 text-green-500">-->
<!--              🌟-->
<!--              <span class="font-bold">Tencent Rhino Bird Open Source Contributor</span>-->
<!--              in Tencent Omi.-->
<!--            </p>-->
<!--            -->
<!--            <p class="py-1 text-red-500">-->
<!--              🏆-->
<!--              <span class="font-bold">Tencent Rhino Bird Open Source Practical Award</span>-->
<!--            </p>-->
<!--            -->
<!--            <p class="py-1 text-yellow-500">-->
<!--              🌟-->
<!--              <span class="font-bold">Alibaba Open Source Contributor</span> in-->
<!--              Alibaba Cloud ( Higress -&#45;&#45; OpenYurt ).-->
<!--            </p>-->
<!--            -->
<!--            <p class="py-1 text-orange-500">-->
<!--              🏅-->
<!--              <span class="font-bold">Champion of the Alibaba Cloud Tianchi 2024 Cloud Native-->
<!--                Programming Challenge</span>-->
<!--            </p>-->
          </div>
        </div>
      </div>
      <!-- 🎯 Looking for Jobs -->
      <div class="flex flex-col justify-between w-full gap-5 mt-4 md:gap-0 md:flex-row">
        <!-- 工作机会 -->
        <div
          class="bg-stripe w-full md:w-[45%] bg-slate-50 border dark:bg-slate-800 dark:border-slate-900 p-4 rounded-xl">
          <p class="text-[12px]">🎯 Looking for Jobs</p>
          <h1 class="mt-2 text-4xl font-bold">工作机会</h1>
          <div class="mt-4 md:text-base lg:text-xl">
            <p class="py-1 text-blue-500">
              💼 Work Experience:
<!--              <a href="https://github.com/LofiSu/LofiSu/blob/main/My%20offer.md" class="underline">myOffer</a>-->
            </p>
            <p class="py-1 text-green-500">🛠️ Internship:</p>
<!--            <ul>-->
<!--              <li class="py-1">-->
<!--                <a href="https://www.bilibili.com/" class="text-pink-500 text-2xl font-bold italic">Bilibili</a>-->
<!--                <span class="text-purple-500">&#45;&#45; OGV（Occupationally Generated Video）Technical Department-->
<!--                  + Value-added Front-End Business Group</span>-->
<!--                <span class="text-green-500 font-mono">`Front-End Engineer`</span>-->
<!--                <span class="text-red-500">-&#45;&#45; `From 2024.7 to Now.`</span>-->
<!--              </li>-->
<!--              <li class="py-1">-->
<!--                <a href="https://www.meituan.com/" class="text-yellow-500 text-2xl font-bold italic">Meituan</a>-->
<!--                <span class="text-blue-500">&#45;&#45; Takeaway business unit Campus team</span>-->
<!--                <span class="text-green-500 font-mono">`From 2024.1 to 2024.6.`</span>-->
<!--              </li>-->
<!--            </ul>-->
          </div>
        </div>
        <!-- 🪁 Interests -->
        <div
          class="bg-stripe w-full md:w-[45%] bg-slate-50 border dark:bg-slate-800 dark:border-slate-900 p-4 rounded-xl">
          <h2 class="text-2xl font-bold">🪁 Interests</h2>
          <ul class="mt-2 md:text-base lg:text-xl">
            <li>🪄 Traveling</li>
            <li>🎶 Producing Music 🎸 Sing 🎤
<!--              My Music: <a href="https://music.163.com/#/artist?id=33710680"-->
<!--                class="underline">网易云音乐主页</a>-->
            </li>
            <li>📸 Photography</li>
          </ul>
          <!-- 📫 How to reach me -->
          <h2 class="mt-4 text-2xl font-bold">📫 How to reach me</h2>
          <ul class="mt-2 md:text-base lg:text-xl">
<!--            <li>Email: <a href="mailto:linsu269@gmail.com" class="underline text-blue-500">lofisuchat@gmail.com</a></li>-->
<!--            <li>GitHub: <a href="https://github.com/LofiSu" class="underline text-blue-500">LofiSu</a></li>-->
<!--            <li>掘金：<a href="https://juejin.cn/user/2351234356882624" class="underline text-blue-500">LofiSu</a></li>-->
<!--            <li>Bilibili: <a href="https://space.bilibili.com/489812144?spm_id_from=333.1007.0.0"-->
<!--                class="underline text-blue-500">空生酥</a></li>-->
            <li>QQ: 1017557616</li>
          </ul>
        </div>
      </div>

      <div class="mt-4 flex w-full flex-col justify-between gap-5 md:flex-row md:gap-0">
        <!-- 音乐 -->
        <div
            class="relative h-52 min-h-[13rem] w-full overflow-hidden rounded-xl sm:h-auto md:h-auto md:w-[39%]"
        >
          <div class="music-bg absolute h-full w-full bg-cover bg-center bg-no-repeat"></div>
          <div class="relative z-10 p-4">
            <p class="text-[12px] text-slate-200">音乐喜好</p>
            <h1 class="mt-1.5 text-4xl font-bold text-white">R&B、</h1>
            <h1 class="mt-1.5 text-4xl font-bold text-white">欧美流行、</h1>
            <h1 class="mt-1.5 text-4xl font-bold text-white">轻音乐</h1>
            <p class="text-right text-sm text-slate-100">《Starboy》</p>
          </div>
        </div>
        <!-- 游戏 -->
        <div
            class="relative h-52 w-full overflow-hidden rounded-xl md:h-auto md:min-h-[13rem] md:w-[59%]"
        >
          <div class="game-bg absolute h-full w-full bg-cover bg-center bg-no-repeat"></div>
          <div class="relative z-10 flex h-full flex-col justify-between p-4">
            <p class="text-[12px] text-slate-50">电子阳痿</p>
            <h1 class="mt-2 flex-1 text-4xl font-bold text-white"> GTA5 / 荒野大镖客2 / 赛博朋克 </h1>
            <p class="mt-2 self-end text-right text-sm text-slate-100">英雄联盟 / league of legends</p>
          </div>
        </div>
      </div>

      <!-- 运动/电影 -->
      <div class="mt-4 flex w-full flex-col justify-between gap-5 md:flex-row md:gap-0">
        <!-- 电影 -->
        <div class="relative h-72 w-full overflow-hidden rounded-xl md:min-h-[18rem] md:w-[58%]">
          <div class="movie-bg absolute h-72 w-full bg-cover bg-center bg-no-repeat"></div>
          <div class="relative z-10 flex h-full flex-col justify-between p-4">
            <p class="text-[12px] text-slate-50">兴趣爱好</p>
            <h1 class="mt-2 flex-1 text-4xl font-bold text-white">科幻 / 文艺 <br />动漫影视剧</h1>
            <p class="mt-2 self-end text-right text-sm text-slate-100">
              “当你不能够再拥有，你唯一可以做的，就是令自己不要忘记” ——《东邪西毒》
            </p>
          </div>
        </div>
        <!-- 运动 -->
        <div class="relative h-72 w-full overflow-hidden rounded-xl md:min-h-[18rem] md:w-[40%]">
          <div class="sport-bg absolute h-72 w-full bg-cover bg-center bg-no-repeat"></div>
          <div class="relative flex h-full flex-col justify-between p-4">
            <p class="text-[12px] text-slate-50">电子竞技</p>
            <h1 class="mt-2 flex-1 text-4xl font-bold italic text-white">Zeus！！！</h1>
            <p class="mt-2 self-end text-right text-sm italic text-slate-100">SKT T1</p>
          </div>
        </div>
      </div>
<!--      &lt;!&ndash; 图片与音乐 &ndash;&gt;-->
<!--      <div class="flex flex-col justify-between w-full gap-5 mt-4 md:gap-0 md:flex-row">-->
<!--        &lt;!&ndash; 图片 &ndash;&gt;-->
<!--        <div class="w-full md:w-[45%] kawaii-bg bg-center bg-no-repeat bg-cover rounded-xl h-52 sm:h-auto"></div>-->
<!--        <div-->
<!--          class="bg-stripe w-full md:w-[50%] bg-slate-50 border dark:bg-slate-800 dark:border-slate-900 p-4 rounded-xl">-->
<!--          <p class="text-[12px]">🎵 Music</p>-->
<!--          <h1 class="mt-2 text-4xl font-bold text-red-600">r&b</h1>-->
<!--          <h1 class="mt-2 text-4xl font-bold text-orange-400">Pop</h1>-->
<!--          <h1 class="mt-2 text-4xl font-bold text-yellow-400">rap</h1>-->
<!--        </div>-->



<!--      </div>-->

<!--      &lt;!&ndash; 图片 &ndash;&gt;-->
<!--      <div class="flex flex-col w-full mt-4">-->
<!--        <img src="../../src/public/hi.jpg" alt="hi" class="w-full rounded-lg" />-->
<!--      </div>-->

    </div>
  </div>
</template>

<script setup>
</script>

<style scoped>
.honer-bg {
  background-image: url("./img/honer.jpg");
}

.music-bg {
  background-image: url("./img/1111.jpg");
  filter: brightness(0.6);
}

.game-bg {
  background-image: url('./img/1.jpg');
  filter: brightness(0.8);
}

.sport-bg {
  background-image: url('./img/333.png');
  filter: brightness(0.6);
}

.movie-bg {
  background-image: url('./img/2.jpg');
  filter: brightness(0.6);
}

.avatar-ping {
  animation: avatarPing 2s ease-in infinite;
}

@keyframes avatarPing {

  0%,
  100% {
    transform: translateX(-50%) translateY(-50%) scale(1.05);
  }

  50% {
    transform: translateX(-50%) translateY(-50%) scale(1.1);
  }
}

.tag-bounce {
  animation: tagBounce 1.5s ease-in infinite;
}

@keyframes tagBounce {

  0%,
  100% {
    transform: translateY(0);
  }

  50% {
    transform: translateY(-10%);
  }
}

.icon-scroll {
  animation: iconScroll 20s linear infinite;
}

@keyframes iconScroll {
  0% {
    transform: translateX(0);
  }

  100% {
    transform: translateX(-50%);
  }
}
</style>
