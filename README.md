## Why Obsidian ?

Welcome to my minimalist Obsidian template project!

Many people just take note using Notepad++ because it is quick to open and quick to start writing. But what about finding back what you wrote? I already witnessed people opening their `new - 131` file in Notepad++ and I bet they struggle finding where they wrote what.

Once I started working on multiple different projects with multiple different deadlines with multiple different teams I quickly realized Notepad++ won't do it anymore. I then started to look for more advanced tools. There are many, but a lot of them trade off the advantage of Notepad++ to have the quickest time-to-be-ready to take notes to effectively propose solutions to sort them nicely.
And all of them shared the same flaw: when organizing your files, you follow the very-well-know file-structure of computers: everything is ordered in folders and subfolders. While it is a very natural way of ordering your thoughts, it forces you to use one dimension to sort them.
Let me explain: You probably want to order your thoughts into different projects, let say, ``Ninja WebApps`` and ``Startup Radar``. But for both of them, you want to split your notes between `Meetings` and `Documentation`. The first problem is that you will probably have to duplicate your subfolders twice, like that:
- Ninja WebApps
	- Meetings
	- Documentations
- Startup Radar
	- Meetings
	- Documentations

More than that, here it looks logical in which order you want to dive into the dimensions: first project-like and then kind-of-note-like. But sometimes it is unclear and you might not be consistent within each project. Finally, what if you want to actually have a view based on the time instead? Should you create a folder each day and then arrange folders as above?
You got it, today's structure is based on one dimension at a time, and it can limit the power of indexing your files in a smarter way.

Obsidian breaks this thinking by having a very convenient `link-oriented` way to organize your notes, while still letting you keeping a folder-file structure if it can re-assure you. Also, Obsidian have tons of tools to help you write something very quickly and classify it very quickly as well, but the trade-off here is that it can be harder to master the tool as it would be with Notepad++.

I invite you to do a quick tour of the main functionalities of Obsidian and of the Markdown format through their official documentation or YouTube videos before starting using this template.

---

## Why a template?

In my opinion, the only serious drawback of Obsidian is its required level of expertise. This is why I suggest using this template to get it in hand quickly and only memorize few shortcuts to boost your productivity at a maximum.

---

## The PACMAN structure

So basically I'm supporting to get rid off the file-directory structure but I just give one in the template. Why is that?

I think a compromise between practice and theory should be found. Many, if not all of us are used to a file-directory structure. To help switch the thinking, I still find it very useful to have a very least hierarchical structure that I named PACMAN. It is derived from the very interesting work of Tiago and his structure PARA, but adapted for a more developer - PO usage in my opinion. Also, having this least structure can greatly help migrating the tool into a new one if necessary, supporting the barely minimum of file-directory structure (Obsidian is not free to use professionally and is not guaranteed to be free for independents forever).

About the PACMAN structure, the idea is the following:
1. **Projects**: the main directory with all your current projects. Usually you want to keep an eye actively on everything inside here. More info at [[README - 1 Projects]].
2. **Agenda**: All generated dailies fall here. More info at [[README - 2 Agenda]].
3. **Concepts**: Fundamental blocks of your second brain. More info at [[README - 3 Concepts - Definitions]] and [[README - 3 Concepts - People]].
4. **Mastery**: Related to Concepts, but are more thought of being something active you want to master. More info at [[README - 4 Mastery]].
5. **Archives**: Keep you Projects folder clean and neat. Everything not active anymore should be dragged to Archives. More info at [[README - 5 Archives]]
6. **Notations**: Everything that is not directly related to your second brain, but related to the tool you are using. Here it is Obsidian, but the day you migrate your tool, you usually want to migrate everything from 1 to 5, but not the sixth folder: Notations.