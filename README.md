# raindrop

This is the home of the `raindrop` obfuscator. It transforms program functions into obfuscated ROP chains that coexist seamlessly with the surrounding software stack and can withstand popular static and dynamic deobfuscation approaches.

`raindrop` takes as input an ELF binary and obfuscates one or more user-defined functions, introducing different ROP-based obfuscations.

This is the high-level workflow:
<br/><br/>
<img src="https://user-images.githubusercontent.com/18199462/113410660-3b1bb500-93b4-11eb-87c2-73dbe051bf4d.png" width="60%" height="60%">
<br/><br/>


The design behind `raindrop` is described in [*Hiding in the Particles: When Return-Oriented Programming Meets Program Obfuscation*](https://ieeexplore.ieee.org/document/9505168) which has appeared in the [DSN 2021](http://dsn2021.ntu.edu.tw/) conference.

## Access
We grant access to the tool and its code for research purposes. Please send an email to [borrello@diag.uniroma1.it](mailto:borrello@diag.uniroma1.it?subject=[raindrop]%20code%20access) with the subject `[raindrop] code access` and specify in the body your name, your affiliation, and your [GITLAB](https://gitlab.com/) username, so we can grant you access to a private repository that we use for the project. We will keep your data confidential.

## Cite
```
@inproceedings{raindrop,
    author={Borrello, Pietro and Coppa, Emilio and D’Elia, Daniele Cono},
    booktitle={2021 51st Annual IEEE/IFIP International Conference on Dependable Systems and Networks (DSN)}, 
    title={Hiding in the Particles: When Return-Oriented Programming Meets Program Obfuscation}, 
    year={2021},
    publisher = {IEEE},
    location = {Virtual Event},
    pages={555-568},
    doi={10.1109/DSN48987.2021.00064}}
}
```
