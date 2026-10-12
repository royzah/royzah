<!-- markdownlint-disable MD033 MD041 -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:cba6f7,50:f5c2e7,100:89b4fa&height=200&section=header&text=Royyan%20Zahir&fontSize=60&fontColor=1e1e2e&fontAlignY=38&desc=I%20break%20things%20at%20every%20layer%20of%20the%20stack&descSize=18&descAlignY=60&descAlign=50&animation=fadeIn" width="100%" alt="Royyan Zahir"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=900&color=F5C2E7&center=true&vCenter=true&width=760&lines=From+the+React+button+to+the+kernel+driver;Senior+Software+Engineer+and+Professional+Bootloop+Witness;PhD+in+wireless+control.+Still+fighting+with+wifi.;Post-quantum+crypto%2C+because+normal+paranoia+got+boring;Catppuccin+Mocha+everywhere.+Yes%2C+everywhere." alt="Typing SVG" /></a>

<img src="https://img.shields.io/badge/based_in-Abu_Dhabi-cba6f7?style=for-the-badge&labelColor=1e1e2e" alt="Based in Abu Dhabi"/>
<img src="https://img.shields.io/badge/PhD-Aalto_University-f5c2e7?style=for-the-badge&labelColor=1e1e2e" alt="PhD Aalto"/>
<img src="https://img.shields.io/badge/coffee-load--bearing-fab387?style=for-the-badge&labelColor=1e1e2e" alt="Coffee: load-bearing"/>
<img src="https://img.shields.io/badge/sanity-deprecated-f38ba8?style=for-the-badge&labelColor=1e1e2e" alt="Sanity: deprecated"/>

</div>

## <img src="https://img.shields.io/badge/-%20-cba6f7?style=flat-square" height="20"/> Hi, I'm Royyan

I'm the person who gets pulled into the meeting when the bug is "somewhere between the web dashboard and the silicon". It usually isn't hard to find, because I wrote most of what's in between. Full-stack by day, DevOps by pager, embedded by some deep personal flaw that a PhD in electrical engineering did nothing to fix. It just gave me a stronger vocabulary for it.

The career so far looks like a speedrun of "how many timezones can one person debug in". Bare-metal firmware on Cortex-M in Singapore. LoRa sensors on the Korean DMZ, where "zero-failure deployment" is a requirement and not a vibe. Factory monitoring and a 24 kW DC-DC converter startup in Helsinki, where I also picked up a doctorate in getting control systems to survive wireless links that hate them. Now it's drones, secure embedded Linux and zero-trust networking in Abu Dhabi. The weather changed a lot. The serial console did not.

## <img src="https://img.shields.io/badge/-%20-f5c2e7?style=flat-square" height="20"/> What I actually do all day

Mostly I build **embedded Linux that boots, proves who it is, and refuses to talk to strangers**. That means Yocto BSPs across three SoC vendors at once (NXP i.MX, NVIDIA Jetson, Qualcomm), because apparently suffering on one vendor wasn't educational enough. Secure boot, OP-TEE trusted apps, remote attestation, PKCS#11 and HSMs, A/B OTA updates that roll back by themselves when I inevitably ship something stupid. If you've never watched a board fail to boot with no output at all and felt personally judged, I envy you.

Then there's the network layer, where every device gets a hardware-rooted identity and every link is encrypted and permission-checked, over whatever radio is lying around. I wrote a hybrid post-quantum Noise handshake (X25519 + ML-KEM-768) for [rust-libp2p](https://github.com/royzah/rust-libp2p) and taught the [snow](https://github.com/royzah/snow) Noise library about ML-KEM, because the quantum computers aren't here yet and I like to be emotionally prepared. I also fixed some concurrency races in [go-rosenpass](https://github.com/royzah/go-rosenpass), a sentence that sounds calm and was not.

Further down, it gets weirder: flight controllers on NuttX and PX4, a deterministic Ethernet backbone with a 1 ms control budget, a GNSS antenna array, software-defined radios, LoRa PHY experiments, and an offline particle filter that tries to locate you using only cell towers. Upstream, I've made A/B OTA actually work on Qualcomm Linux, which mostly meant finding a tool that silently threw away the slot flags and a retry counter living one bit off from where it should have been. Embedded is just regular programming, except the stack trace is a blinking LED.

Somewhere at the top of all this there are also React consoles, Go and FastAPI control planes, Kubernetes clusters and cloud bills. Somebody has to draw the drones on a map.

## <img src="https://img.shields.io/badge/-%20-89b4fa?style=flat-square" height="20"/> The stack (in order of how often it hurts me)

<div align="center">

<img src="https://skillicons.dev/icons?i=go,rust,py,ts,c,cpp,bash,nix&perline=8" alt="Daily languages"/>

<sub>Go, Rust, Python and TypeScript every day, which means I hold four contradictory opinions about error handling and all of them are angry. Go turned <code>if err != nil</code> into my personality. Rust's borrow checker is right every time, and it's insufferable about it. Python lets me do whatever I want, which is exactly the problem. TypeScript is JavaScript wearing a tie to a job interview. C is the one that remembers what I did.</sub>

<br><br>

<img src="https://img.shields.io/badge/Yocto_/_OpenEmbedded-1e1e2e?style=for-the-badge&logo=linux&logoColor=f9e2af"/>
<img src="https://img.shields.io/badge/NXP_i.MX-1e1e2e?style=for-the-badge&logo=nxp&logoColor=f9e2af"/>
<img src="https://img.shields.io/badge/NVIDIA_Jetson-1e1e2e?style=for-the-badge&logo=nvidia&logoColor=a6e3a1"/>
<img src="https://img.shields.io/badge/Qualcomm-1e1e2e?style=for-the-badge&logo=qualcomm&logoColor=89b4fa"/>
<img src="https://img.shields.io/badge/ARM-1e1e2e?style=for-the-badge&logo=arm&logoColor=74c7ec"/>
<img src="https://img.shields.io/badge/NuttX_/_PX4-1e1e2e?style=for-the-badge&logoColor=f38ba8"/>
<img src="https://img.shields.io/badge/OP--TEE-1e1e2e?style=for-the-badge&logoColor=cba6f7"/>
<img src="https://img.shields.io/badge/WireGuard-1e1e2e?style=for-the-badge&logo=wireguard&logoColor=f38ba8"/>
<br>
<img src="https://skillicons.dev/icons?i=linux,raspberrypi,arduino,cmake,qt&perline=5" alt="Embedded"/>

<sub>Close to the metal. A bitbake run is basically a meditation retreat: you start it, you go live a full life, you come back, and it failed on a checksum.</sub>

<br><br>

<img src="https://skillicons.dev/icons?i=docker,kubernetes,terraform,githubactions,gitlab,jenkins,aws,azure,gcp,grafana,prometheus,nginx&perline=12" alt="Infra"/>

<sub>Orchestrating chaos like a drunk conductor. Every cluster I own is reproducible, version-pinned and fully documented, and I'm also lying about one of those.</sub>

<br><br>

<img src="https://skillicons.dev/icons?i=react,nextjs,vue,angular,tailwind,nodejs,express,fastapi,django,flask,dotnet&perline=11" alt="Web"/>

<sub>Day 2,847 of trying to center a div. The div remains uncentered. I remain unhinged.</sub>

<br><br>

<img src="https://skillicons.dev/icons?i=postgres,redis,sqlite,mongodb,mysql,elasticsearch,kafka,rabbitmq&perline=8" alt="Data"/>

<sub>Eight different places to lose your data. Choose wisely.</sub>

<br><br>

<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,js,java,cs,r,matlab&perline=8" alt="Also on the resume"/>

<sub>Machine learning, plus the languages I swear I don't use anymore. I also built a crypto trading model that has never touched real money, which makes it the most responsible trading model on the internet.</sub>

</div>

## <img src="https://img.shields.io/badge/-%20-94e2d5?style=flat-square" height="20"/> The setup (a color-coordinated cry for help)

<div align="center">

<img src="https://img.shields.io/badge/Ubuntu-1e1e2e?style=for-the-badge&logo=ubuntu&logoColor=fab387"/>
<img src="https://img.shields.io/badge/Nix_flakes-1e1e2e?style=for-the-badge&logo=nixos&logoColor=89b4fa"/>
<img src="https://img.shields.io/badge/Ghostty-1e1e2e?style=for-the-badge&logo=ghostty&logoColor=cba6f7"/>
<img src="https://img.shields.io/badge/zsh_+_starship-1e1e2e?style=for-the-badge&logo=starship&logoColor=f5c2e7"/>
<img src="https://img.shields.io/badge/tmux-1e1e2e?style=for-the-badge&logo=tmux&logoColor=a6e3a1"/>
<img src="https://img.shields.io/badge/LazyVim-1e1e2e?style=for-the-badge&logo=neovim&logoColor=94e2d5"/>
<img src="https://img.shields.io/badge/Catppuccin_Mocha-cba6f7?style=for-the-badge&labelColor=1e1e2e"/>

</div>

Ubuntu underneath, because I like my OS boring and my problems interesting. Every project gets its own Nix flake and a direnv `.envrc`, so I `cd` into a repo and the right Go, Rust and Python toolchains just show up like a well-trained butler. Running Nix on Ubuntu means NixOS people think I'm a coward and Ubuntu people think I joined a cult. They're both right. Ask me to `apt install` a compiler and watch me age in real time.

On top of that it's Ghostty, zsh with starship, tmux and Neovim (LazyVim), and all of it is Catppuccin Mocha. Terminal, editor, status bar, this README. If I could theme my landlord, I would. The [dotfiles](https://github.com/royzah/dotfiles) come with a no-sudo installer for build servers, which I wrote after the third build server where somebody said "you don't need root for that, right?"

Commits are conventional. `fix: fix the fix` is technically valid, and I will die on that hill. `chore:` is for anything I'd rather not explain.

## <img src="https://img.shields.io/badge/-%20-a6e3a1?style=flat-square" height="20"/> Current status

```console
$ cd ~/Code/some-yocto-thing
direnv: loading .envrc
direnv: using flake
[ fetching half the internet for a change I did not make ]

$ kas build
NOTE: Tasks Summary: Attempted 9412 tasks of which 9411 didn't need to be rerun and 1 failed.

$ picocom -b 115200 /dev/ttyUSB0
U-Boot 2024.04
Starting kernel ...
[ silence. the board has chosen violence. ]

$ git commit -m "fix: it boots now (do not ask why)"
```

## <img src="https://img.shields.io/badge/-%20-f9e2af?style=flat-square" height="20"/> Achievements, kind of

I have mastered "it works on my machine", where the machine is defined by a flake lock file, so technically it works on yours too and you're just doing it wrong. I can produce an infinite loop in any language and a boot loop on any SoC vendor. I hold a doctorate in turning simple tasks into complex problems, issued by an actual university, so it's legally binding. Work-life balance is still in beta, and the beta has been extended.

## <img src="https://img.shields.io/badge/-%20-fab387?style=flat-square" height="20"/> The five stages of debugging

1. "That can't happen."
2. "That doesn't happen on my machine."
3. "That shouldn't happen."
4. "Why is it working now?!"
5. "Ship it before it realizes it's broken."

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=royzah&theme=catppuccin-mocha&hide_border=true" alt="GitHub streak"/>

<sub>Most of my commits live in private repos, so this graph is the visible tip of a very large, very sleep-deprived iceberg.</sub>

</div>

```python
# I have no idea why this works, but it does.
# If you change this code, it will break.
# If you don't change this code, it will still break.
#
# UPDATE: Past me is an idiot
# UPDATE 2: Current me is also an idiot
# UPDATE 3: The idiot was the bootloader all along
```

<div align="center">

<em>"Man is sometimes extraordinarily, passionately, in love with suffering."</em>
<br>
<strong>-- Fyodor Dostoevsky</strong>
<br>
<sub>He would have loved Yocto.</sub>

<br><br>

<a href="mailto:royyan.zahir@gmail.com"><img src="https://img.shields.io/badge/royyan.zahir@gmail.com-1e1e2e?style=for-the-badge&logo=gmail&logoColor=f38ba8"/></a>
<a href="https://www.linkedin.com/in/royyan-zahir-521b3b39b"><img src="https://img.shields.io/badge/LinkedIn-1e1e2e?style=for-the-badge&logo=linkedin&logoColor=89b4fa"/></a>
<br><br>
<img src="https://komarev.com/ghpvc/?username=royzah&color=cba6f7&style=for-the-badge&label=lost+souls+who+wandered+in" alt="Profile views"/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:89b4fa,50:f5c2e7,100:cba6f7&height=120&section=footer" width="100%" alt="footer"/>

</div>
