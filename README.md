<h3 align="center">👋 I'm Nicolas a Student at the University of Paris X </h3>
<br>
Currently :
<br>

- 🧑🏻‍🎓 Student in Computer Methods Applied to Business Management

- 👨🏻‍💻 Learning **Python** with projects

- 💻 All of my projects are available in my [Portfolio](https://nicolas-cordeiro.webflow.io/)

- 📫 To contact me **nicolas.cordeiro@parisnanterre.fr**

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="python" width="40" height="40"/> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="java" width="40" height="40"/></a> </p>

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://www.linkedin.com/in/cordeiro-nicolas/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/cordeiro-nicolas/" height="30" width="40" /></a>
</p>
<br>

```mermaid
flowchart LR

%% Colors %%
linkStyle default stroke-width:2px
classDef blue fill:#2C4890FF,stroke:#000,stroke-width:2px,color:#fff
classDef orange fill:#F27420FF,stroke:#000,stroke-width:2px,color:#fff
classDef red fill:#D70606FF,stroke:#000,stroke-width:2px,color:#fff
classDef green fill:#1EA804FF,stroke:#000,stroke-width:2px,color:#fff

%% Goals Database%%
%% 0 %%
G(Goals):::blue <===> |Connects To| P[(Projects)]:::blue

%% Deadline %%
%% 1,2,3,4 %%
P ---o |Has| PD(Deadline):::orange
PD ---x |Is| MT([Met]):::green
PD ---- |Is| OV(Overdue):::red ---> |Push| FOV{X Days}

%% Tasks %%
%% 5,6,7, 8 %%
P ---o |Has| PT(Tasks):::orange
PT ---x |IS| IC([Incomplete]):::red
PT ---- C([Complete]):::green
C ---> R[[Review]]


%% Review %%
%% 9 %%
R -..-> |Creates New| G

%% Link Colors %%
linkStyle 0 stroke:blue
linkStyle 1,5 stroke:orange
linkStyle 2,7 stroke:green
linkStyle 3,6 stroke:red

```

