<!-- markdownlint-disable MD033 MD041 -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:cba6f7,50:f5c2e7,100:89b4fa&height=200&section=header&text=Royyan%20Zahir&fontSize=60&fontColor=1e1e2e&fontAlignY=38&desc=I%20break%20things%20at%20every%20layer%20of%20the%20stack&descSize=18&descAlignY=60&descAlign=50&animation=fadeIn" width="100%" alt="Royyan Zahir"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=900&color=F5C2E7&center=true&vCenter=true&width=760&lines=Senior+Software+Engineer.+Frontend+to+firmware.;From+the+React+button+to+the+kernel+driver;PhD+in+wireless+control.+Still+fighting+with+wifi.;Post-quantum+crypto%2C+because+normal+paranoia+got+boring;Catppuccin+Mocha+everywhere.+Yes%2C+everywhere." alt="Typing SVG" /></a>

<img src="https://img.shields.io/badge/based_in-Abu_Dhabi-cba6f7?style=for-the-badge&labelColor=1e1e2e" alt="Based in Abu Dhabi"/>
<img src="https://img.shields.io/badge/PhD-Aalto_University-f5c2e7?style=for-the-badge&labelColor=1e1e2e" alt="PhD Aalto"/>
<img src="https://img.shields.io/badge/coffee-load--bearing-fab387?style=for-the-badge&labelColor=1e1e2e" alt="Coffee: load-bearing"/>
<img src="https://img.shields.io/badge/work--life_balance-finally_shipped-a6e3a1?style=for-the-badge&labelColor=1e1e2e" alt="Work-life balance: finally shipped"/>

</div>

## <img src="https://img.shields.io/badge/-%20-cba6f7?style=flat-square" height="20"/> Hi, I'm Royyan

I get pulled in when the bug is "somewhere between the dashboard and the silicon". Usually I wrote both ends. Full-stack, DevOps, embedded. The PhD didn't fix that, it just gave me better words for it.

Firmware in Singapore, LoRa sensors on the Korean DMZ, power electronics in Helsinki, drones and platforms in Abu Dhabi. The weather changed. The bugs did not.

## <img src="https://img.shields.io/badge/-%20-f5c2e7?style=flat-square" height="20"/> What I actually do

**Normal software.** React frontends, Go and FastAPI backends, Postgres, Kubernetes, the whole "it's just a CRUD app" lie. Real-time maps and live video, because static pages were too relaxing.

**Hardware, when the software isn't hard enough.** Yocto BSPs, embedded Linux, flight controllers, radios. Regular programming, except the stack trace is a blinking LED.

## <img src="https://img.shields.io/badge/-%20-f9e2af?style=flat-square" height="20"/> Upstream (unpaid, but with code review from strangers)

**[Apache NuttX](https://github.com/apache/nuttx/pulls?q=author%3Aroyzah)** - 30+ PRs, mostly merged. Taught an RTOS that user space can't be trusted: bounded syscalls, process capabilities, no poking kernel memory. Also hardware crypto and RNG on NXP i.MX9 and i.MXRT, Pixhawk 6X-RT board support, and a ChaCha fix because GCC 15 had opinions.

**[Qualcomm Linux](https://github.com/qualcomm-linux/meta-qcom/pulls?q=author%3Aroyzah)** - Made A/B OTA actually work. A partition tool silently dropped the slot flags, and the retry counter sat one bit off. Off-by-one, but in bits. Plus Yocto recipes, TF-A, U-Boot, kernel and OP-TEE bring-up across meta-qcom, qcom-ptool and friends.

**[libp2p](https://github.com/libp2p/rust-libp2p/pulls?q=author%3Aroyzah) and [snow](https://github.com/mcginty/snow/pulls?q=author%3Aroyzah)** - A hybrid post-quantum Noise handshake (X25519 + ML-KEM-768): spec, Rust code, and ML-KEM in the Noise library underneath. Also QUIC unreliable datagrams. The quantum computers aren't here yet, but I like to be emotionally prepared.

**[PX4](https://github.com/PX4/PX4-Autopilot/pulls?q=author%3Aroyzah), [QGroundControl](https://github.com/mavlink/qgroundcontrol/pulls?q=author%3Aroyzah), [OP-TEE](https://github.com/OP-TEE/optee_os/pulls?q=author%3Aroyzah)** - A drone should check whether it's armed by reading one register, not two that disagree. Network Remote ID so the drone can tell the authorities who it is. Deterministic ECDSA, because randomness is great everywhere except your signatures.

## <img src="https://img.shields.io/badge/-%20-89b4fa?style=flat-square" height="20"/> The stack (sorted by how often it hurts)

<div align="center">

<img src="https://skillicons.dev/icons?i=go,rust,py,ts,c,cpp,bash,nix&perline=8" alt="Daily languages"/>

<sub>Four daily languages, four angry opinions on error handling.</sub>

<br><br>

<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,nodejs,fastapi,django,postgres,redis,kafka&perline=9" alt="Web and data"/>

<sub>Day 2,847 of trying to center a div. The div remains uncentered.</sub>

<br><br>

<img src="https://skillicons.dev/icons?i=docker,kubernetes,terraform,githubactions,aws,azure,gcp,grafana,prometheus&perline=9" alt="Infra"/>

<sub>Reproducible, version-pinned and documented. One of those is a lie.</sub>

<br><br>

<img src="https://img.shields.io/badge/Yocto-1e1e2e?style=for-the-badge&logo=linux&logoColor=f9e2af"/>
<img src="https://img.shields.io/badge/NuttX-1e1e2e?style=for-the-badge&logoColor=f38ba8"/>
<img src="https://img.shields.io/badge/Qualcomm-1e1e2e?style=for-the-badge&logo=qualcomm&logoColor=89b4fa"/>
<img src="https://img.shields.io/badge/NXP_i.MX-1e1e2e?style=for-the-badge&logo=nxp&logoColor=f9e2af"/>
<img src="https://img.shields.io/badge/NVIDIA_Jetson-1e1e2e?style=for-the-badge&logo=nvidia&logoColor=a6e3a1"/>
<img src="https://img.shields.io/badge/ARM-1e1e2e?style=for-the-badge&logo=arm&logoColor=74c7ec"/>

<sub>A bitbake run is a meditation retreat: start it, go live your life, come back, checksum failed.</sub>

</div>

## <img src="https://img.shields.io/badge/-%20-94e2d5?style=flat-square" height="20"/> The setup

<div align="center">

<img src="https://img.shields.io/badge/Ubuntu-1e1e2e?style=for-the-badge&logo=ubuntu&logoColor=fab387"/>
<img src="https://img.shields.io/badge/Nix_flakes-1e1e2e?style=for-the-badge&logo=nixos&logoColor=89b4fa"/>
<img src="https://img.shields.io/badge/Ghostty-1e1e2e?style=for-the-badge&logo=ghostty&logoColor=cba6f7"/>
<img src="https://img.shields.io/badge/tmux-1e1e2e?style=for-the-badge&logo=tmux&logoColor=a6e3a1"/>
<img src="https://img.shields.io/badge/LazyVim-1e1e2e?style=for-the-badge&logo=neovim&logoColor=94e2d5"/>
<img src="https://img.shields.io/badge/Catppuccin_Mocha-cba6f7?style=for-the-badge&labelColor=1e1e2e"/>

</div>

Nix flakes on Ubuntu: NixOS people think I'm a coward, Ubuntu people think I joined a cult. Both are right. If I could theme my landlord in Catppuccin, I would. [Dotfiles here](https://github.com/royzah/dotfiles).

## <img src="https://img.shields.io/badge/-%20-a6e3a1?style=flat-square" height="20"/> Current status

```console
$ npm run dev
ready on http://localhost:3000

$ docker compose up
works on my machine

$ kubectl apply -f prod.yaml
CrashLoopBackOff

$ git commit -m "fix: it works now (do not ask why)"
```

## <img src="https://img.shields.io/badge/-%20-fab387?style=flat-square" height="20"/> The five stages of debugging

1. "That can't happen."
2. "That doesn't happen on my machine."
3. "That shouldn't happen."
4. "Why is it working now?!"
5. "Ship it before it realizes it's broken."

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=royzah&theme=catppuccin-mocha&hide_border=true" alt="GitHub streak"/>

<sub>Most commits live in private repos. This is the tip of the iceberg.</sub>

</div>

<div align="center">

<em>"Man is sometimes extraordinarily, passionately, in love with suffering."</em>
<br>
<strong>-- Fyodor Dostoevsky</strong>
<br>
<sub>He would have loved CSS.</sub>

<br><br>

<a href="mailto:royyan.zahir@gmail.com"><img src="https://img.shields.io/badge/royyan.zahir@gmail.com-1e1e2e?style=for-the-badge&logo=gmail&logoColor=f38ba8"/></a>
<a href="https://www.linkedin.com/in/royyan-zahir-521b3b39b"><img src="https://img.shields.io/badge/LinkedIn-1e1e2e?style=for-the-badge&logo=linkedin&logoColor=89b4fa"/></a>
<br><br>
<img src="https://komarev.com/ghpvc/?username=royzah&color=cba6f7&style=for-the-badge&label=lost+souls+who+wandered+in" alt="Profile views"/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:89b4fa,50:f5c2e7,100:cba6f7&height=120&section=footer" width="100%" alt="footer"/>

</div>
