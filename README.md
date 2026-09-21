# Gregor von Laszewski

*  Accounts: [LINK to your Piazza account post]

Note:
*  put files in `<repor>/assignments/week3/`
*  Update all YOURREPO


## Week 4:  Due Sep 24, 2026, 9am

- [ ] "Assignment W4.1 VM on local machine via Makefile"

    - [ ] Pick a local VM framework. Make sure it is installed. Which one did you pick? _________
    - [ ] Write a Makefile with all the targets that you need (which are they?) to manage a single VM
    - [ ] Can you manage multiple machines? provide a sample in week4/multiple-vms.md
    - [ ] How do you organize different Makefiles for different local and cloud environments
          (tip directories) there re other ways to do this, but directories are easy.
          Point to a document and sample showing this for two clouds (you can use local once or jetstream, chameleon)

!!! note note "Assignment W4.2 VM on Jetstream 2"

    1. Pick a local VM framework. Make sure it is installed.
    2. Write a Makefile with all the targets that you need (which are they?) to manage a single VM
    3. Can you manage multiple machines? How.

!!! note note "Assignment W4.3 VM on Chameleon Cloud"

    1. Pick a local VM framework. Make sure it is installed.
    2. Write a Makefile with all the targets that you need (which are they?) to manage a single VM

!!! note note "Assignment W4.4 Review Python"

    In preparation for the upcoming weeks, please review your python knowledge. You can any resource you like, but we have provided a large amount of information about python (which you do not need all of it.) Therefore we recommend to strategically review sections that will be instrumental to Clouds, DevOps, and AI.
    If there are any issues, please use Piazza to ask and we can narrow it down. This is a relatively simple activity and it should not take long. If it takes more than 3 hours  please use Piazza to find out where you may need some more help.

    Please review:
        
    1. Setting up  python virtual environment. 
        * You can use the one you use usually use such as venv or pyenv.
        * Typically we discourage using conda and miniconda due to the potential that 
            hundreds of unneeded libraries may be downloaded or a low level conflict may arise. For your project you will be asked not to use conda to keep the vms and containers clean. Use of conda has to be justified in a detailed justification and outline why other python virtualization technologies can not be used. 
        * please not that the openstack commandline tool must be installed with pipx 
    
        See: [link](/section/python/python-install.md/#venv)
    2. Using 
        
        * pip install
        * pipx install

        See: [link](/section/python/python-pipx.md)

    3. Review how to use import statements such as `os.system`
        Write a program that uses os.sytem("ls") (windows users must be in gitbash to make that work or in a vm using Linux.

    4. Review how to create a __main__ 

    5. Review how to write a function

    5. Review how to pass arguments to the python program from commandline.

    !!! tip 
        I recommend click instead of argparse as there is a direct correlation between function name and parameters. click provides ease augmentations befor the function to transform it for you to a commanline interface. In other frameworks you have to do much more.
            
        See: [link](/section/python/python-click.md)

    6. Review how to run shell commands from within python 

        See: [link](/Users/grey/work/cloudmesh-ai-lecture/docs/section/python/python-subprocess.md)

        Focus on `os.system()` and `supbrocess.run()`
    


## Week 3

* [ ] Assignment W3.1: VM on Jetstream (Due Sep 17, 2026, 9am)
  * [ ] Start a VM on Jetstream and follow the tutorial provided.
  * [ ] Improve the tutorial while creating pull requests in the lecture notes if you see issues.
  * [ ] Document your activity with a screenshot of the terminal (800x600).
  * [ ] [VM.MD](https://github.com/cloudmesh-ai-luc/YOURREPO/blob/main/assignments/week3/vm.md)


* [ ] Assignment W3.2: VM on Chameleon Cloud (Due Sep 17, 2026, 9am)
  * [ ] Set your preferred time zone in Chameleon settings.
  * [ ] Make sure you have a key in your `.ssh` dir on your laptop and upload the public key to Chameleon.
  * [ ] Explore the portal and browse around to develop a plan first.
  * [ ] Make a reservation not exceeding 1 hour.
  * [ ] Start up a VM using a Chameleon Cloud image for Ubuntu 24.04 using the smallest image size possible.
  * [ ] Document your activity with a screenshot of the terminal (800x600).
  * [ ] [VM.MD](https://github.com/cloudmesh-ai-luc/YOURREPO/blob/main/assignments/week3/vm.md)


* [ ] Assignment W3.3: OPTIONAL: VM on public cloud (Due Sep 17, 2026, 9am)
  * [ ] Optional: Create a VM on a cloud of your choice (AWS, Azure, Google) using the free tier.
  * [ ] Document with screenshots how you created your account, ensuring sensitive information is blurred out.
  * [ ] [VM.MD](https://github.com/cloudmesh-ai-luc/YOURREPO/blob/main/assignments/week3/vm.md)


* [ ] Assignment W3.4: Compare (Due Sep 17, 2026, 9am)
  * [ ] Compare your experience between starting a VM on your local machine vs using Chameleon Cloud.
  * [ ] Put all assignment answers into `<repor>/assignments/week3.md`. [LINK]
  * [ ] [VM.MD](https://github.com/cloudmesh-ai-luc/YOURREPO/blob/main/assignments/week3/vm.md)
     
* [ ] Assignment W3.5: README.md (Due Sep 17, 2026, 9am)
  * [ ] put your link here  [LINK]
     
 * [ ] Assignment W3.6 git from commandline
   * [ ] put the url of a pull request here

## Week 2
  
* [ ] Assignment W2.1: Google Account, Piazza Account post cleanup (Due Sep 10, 2026, 9am)
  * [ ] Locate your account post in Piazza and add your google account.
  * [ ] Correct your Chameleon ID to the registered email.
  * [ ] Fix your subject line to `Firstname Lastname (lucid@luc.edu)`.


* [ ] Assignment W2.2: GitHub Repository (Due Sep 10, 2026, 9am)
  * [ ] Verify that you can write into a file in your assigned GitHub repository.
  * [ ] Put something useful into the README such as your first and last name. [LINK]
  * [ ] Upload your public key. [LINK]


* [ ] Assignment W2.3: Backup Your Computer (Due Sep 10, 2026, 9am)
  * [ ] Write a one‑paragraph explanation (4–6 sentences) on why backing up a computer is important. 
  * [ ] List three real‑world consequences of not having a backup.
  * [ ] Choose one backup method and outline the setup steps.
  * [ ] Create a weekly backup schedule (day, time, what to back up).
  * [ ] Research an example from cloud computing where a missing backup strategy led to issues and write a short incident case.
  * [ ] Submit to `/assignments/week2/backup.md`. [LINK]


* [ ] Assignment W2.4: Local VM (Due Sep 10, 2026, 9am)
  * [ ] Windows: Install a terminal on Windows (Git Bash/WSL). [Which OS do you have?
  * [ ] Pick a hypervisor (VirtualBox, VMware, Hyper-V, Multipass). [Which?]
  * [ ] Create and start a minimal VM (e.g., Ubuntu 22.04).
  * [ ] Capture proof of login with a terminal screenshot (≤ 800×600 px) showing your prompt and a command.
  * [ ] Write/update the tutorial in `assignments/week1/local-vm.md` and save the screenshot as `assignments/week1/vm-login.png`. [LINK/s]


* [ ] Assignment W2.5: Project proposal (Due Sep 10, 2026, 9am)
  * [ ] Start working towards a project proposal and fill out administrative fields and text. [LINK]


# Week 1

  * [ ] Assignment W1.1: What hardware do you have? (Past Due) [LINK]
  * [ ] Fill out the LUC Hardware Questionnaire.


* [ ] Assignment W1.2: Lecture review (Past Due)
  * [ ] Review all sections under LECTURES -> INTRODUCTIONS and post questions on Piazza.


* [ ] Assignment W1.3: Look over the assignment sections (Past Due)
  * [ ] Review all sections under ASSIGNMENTS (Overview and weekly sections).


* [ ] Assignment W1.4: Create class accounts (Past Due)
  * [ ] Create an account on access-ci.org.
  * [ ] Create an account on chameleoncloud.org.
  * [ ] Set up a GitHub account.
  * [ ] Post account information to Piazza under the accounts category. [LINK]


* [ ] Assignment W1.5: Work ahead: Refresh knowledge about Python and Linux (Past Due)
  * [x] Review optional material in the class documentation.


* [ ] Assignment W1.6: Improve the Web Site (Past Due)
  * [ ] Update errors or notify instructors throughout the semester.


