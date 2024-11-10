---
permalink: /
title: "Rishabh Iyer"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a postdoctoral researcher working with [Sylvia Ratnasamy](https://people.eecs.berkeley.edu/~sylvia/) and [Scott Shenker](http://www.icsi.berkeley.edu/icsi/people/shenker) at UC Berkeley. I completed my PhD at EPFL, under the supervision of [George Candea](http://dslab.epfl.ch/people/candea/) and [Katerina Argyraki](https://people.epfl.ch/katerina.argyraki?lang=en). Prior to joining EPFL, I received a bachelors from IIT Bombay.

I am a computer systems researcher (broadly construed), and most of my work lies at the intersection of systems, networking, hardware and formal verification. My current research focuses on developing techniques that enable developers to reason precisely about the expected performance of their systems _before_ they are deployed. My [dissertation work](/files/thesis.pdf) introduced the notion of latency interfaces---simple, succinct programs that summarize a system’s latency just
like semantic interfaces such as code documentation and specifications summarize functionality---and was awarded the [ACM SIGOPS Dennis M. Ritchie Award](https://www.sigops.org/awards/dmr/), the [Eurosys Roger Needham PhD Award](https://www.eurosys.org/awards/roger-needham-phd-award), and the [Dimitris N. Chorafas Award](https://www.weizmann.ac.il/feinberg/about/dimitris-n-chorafas-prize/about-foundation-and-prize).

Here is my [CV](/files/rishabh_cv.pdf) (updated Aug 2024).

<span style="color:red">**I am on the academic job market for 2024–2025. Please reach out if you’re hiring!**</span>

Selected Publications
-------

**[Fast, Flexible, and Practical Kernel Extensions](/files/kflex.pdf)**   
_Kumar Kartikeya Dwivedi, Rishabh Iyer, Sanidhya Kashyap._ <br>
SOSP 2024. <br>
<span style="color:red">**Also accepted to the Linux Plumbers Conference 2024**</span>. <br>
[[slides]](files/kflex-slides.pdf) [[code]](https://github.com/rs3lab/KFlex)


**[Automatically Reasoning About How Systems Code Uses the CPU Cache](/files/cfar.pdf)**  
_Rishabh Iyer, Katerina Argyraki, George Candea._ <br>
OSDI 2024. <br>
<span style="color:red">**Also accepted to the Linux Plumbers Conference 2024**</span>.<br>
[[slides]](files/cfar-slides.pptx) [[talk video]](https://www.youtube.com/watch?v=QpgOxTcvCrY)

**[Performance Interfaces for Hardware Accelerators](/files/lpn.pdf)**  
_Jiacheng Ma, Rishabh Iyer, Sahand Kashani, Mahyar Emami, Thomas Bourgeat, George Candea._<br>
OSDI 2024.<br>
[[slides]](files/lpn-slides.pptx) [[code]](https://github.com/dslab-epfl/lpn) [[talk video]](https://www.youtube.com/watch?v=S6BtXr-bFqk)

**[Achieving Microsecond-Scale Tail Latency Efficiently with Approximate Optimal Scheduling](/files/concord.pdf)**  
_Rishabh Iyer, Musa Unal, Marios Kogias, George Candea._<br> 
SOSP 2023.<br>
[[slides]](files/concord-slides.pptx) [[code]](https://github.com/dslab-epfl/concord) [[talk video]](https://www.youtube.com/watch?v=VMSdUr-91_U)

**[Performance Interfaces for Network Functions](/files/pix.pdf)**  
_Rishabh Iyer, Katerina Argyraki, George Candea._ <br> 
NSDI 2022.  <br>
[[slides]](files/pix_slides.pdf) [[talk video]](https://www.youtube.com/watch?v=iM3R2Gp0PWo) [[code]](https://github.com/dslab-epfl/pix)

**[Performance Contracts for Software Network Functions](/files/bolt.pdf)**  
_Rishabh Iyer, Luis Pedrosa, Arseniy Zaostrovnykh, Solal Pirelli, Katerina Argyraki, George Candea._ <br> 
NSDI 2019.  <br>
[[slides]](files/bolt_slides.pdf) [[talk video]](https://www.youtube.com/watch?v=cV8pCGiTxgQ) [[code]](https://github.com/bolt-perf-contracts/bolt) [[website]](https://bolt-perf-contracts.github.io)

Additional Publications
-------

**[The Case for Validating Inputs in Software-Defined WANs](/files/hodor.pdf)**  
_Alexander Krentsel, Rishabh Iyer, Isaac Keslassy, Sylvia Ratnasamy, Anees Shaikh, Rob Shakir._ <br>
HotNets 2024. <br>

**[Revisiting Cache Freshness for Emerging Real-Time Applications](/files/freshness.pdf)**  
_Ziming Mao, Rishabh Iyer, Scott Shenker, Ion Stoica._ <br>
HotNets 2024. <br>

**[If Layering Is Useful, Why Not Sublayering?](/files/sublayering.pdf)**  
_Rathin Singha, Rishabh Iyer, Charles Liu, Caleb Terrill, Todd Millstein, Scott Shenker, George Varghese._ <br>
HotNets 2024. <br>

**[The Case for Performance Interfaces for Hardware Accelerators](/files/perf-interf-accel.pdf)**  
_Rishabh Iyer, Jiacheng Ma, Katerina Argyraki, George Candea, Sylvia Ratnasamy._ <br>
HotOS 2023. <br>
[[slides]](files/accel-hotos-slides.pptx)

**[Bypassing the Load Balancer Without Regrets](/files/crab.pdf)**  
_Marios Kogias, Rishabh Iyer, Edouard Bugnion._  <br>
SOCC 2020. <br>
[[talk video]](https://drive.google.com/file/d/1pG8Tbkn3obZhSSzWJGVsVcQ5kAziMg07/view?usp=sharing) [[code]](https://github.com/epfl-dcsl/crab)  

**[Verifying Software Network Functions with No Verification Expertise](/files/vigor.pdf)**  
_Arseniy Zaostrovnykh, Solal Pirelli, Rishabh Iyer, Matteo Rizzo, Luis Pedrosa, Katerina Argyraki, George Candea._  <br>
SOSP 2019.  <br>
[[slides]](https://vigor-nf.github.io/slides.pdf) [[talk video]](https://sosp19.rcs.uwaterloo.ca/videos/D2-S1-P4.mp4) [[code]](https://github.com/vigor-nf/vigor) [[website]](https://vigor-nf.github.io/)  

**[Performance Modelling and Dynamic Scheduling for Heterogeneous-ISA Multi-Core Architectures](files/btp.pdf)**  
_Nirmal Boran, Dinesh Yadav, Rishabh Iyer._  <br>
VDAT 2019.  <br>
<span style="color:red">**Awarded Best Paper**</span>. <br>
[[slides]](files/vdat19_slides.pdf)

**[Automated Synthesis of Adversarial Workloads for Network Functions](files/castan.pdf)**    
_Luis Pedrosa, Rishabh Iyer, Arseniy Zaostrovnykh, Jonas Fietz, Katerina Argyraki._  <br>
SIGCOMM 2018. <br>
[[slides]](files/castan_slides.pdf) [[talk video]](https://www.youtube.com/watch?v=1BjeaNvmBwQ&t=1571s) [[code]](https://github.com/nal-epfl/castan) [[website]](https://pedrosa.2y.net/Projects/CASTAN)
