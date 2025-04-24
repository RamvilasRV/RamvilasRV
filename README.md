Hi there.. 👋

```python
def Ramvilas(coffee, debug_mode=False):
    """
    Initialize Ramvilas with caffeine power and a sprinkle of humor.

    Parameters:
        coffee (int): Number of coffee cups consumed (more cups, more bugs fixed).
        debug_mode (bool): If True, prints random dev jokes during execution.

    Returns:
        Developer: A quirky Python enthusiast ready to code and conquer bugs.
    """
    focus = "Python Development"
    passion = "Crafting products people love (and occasionally rage-quit)"
    bug_squashing_level = coffee * 10  # Each coffee boosts bug-zapping power
    side_quests = ["Automating boring stuff", "Googling regex for the 100th time", "Arguing tabs vs spaces"]

    if debug_mode:
        print("Why did the Python dev quit? Too many *circular imports* in life!")
    
    while True:
        try:
            code = write_awesome_code(focus, passion)
            if bug_squashing_level > 50:
                print("Warning: Excessive coffee detected. May refactor entire codebase at 2 AM.")
            return code
        except SyntaxError:
            print("Oops, forgot a colon again. Time for more coffee!")
            coffee += 1
            bug_squashing_level = coffee * 10
        except KeyboardInterrupt:
            print("Ctrl+C life. Ramvilas is off to debug the coffee machine!")
            break

    return "Ramvilas: Powered by Python, coffee, and a questionable sense of humor."
```

[![RamvilasRV's GitHub stats](https://github-readme-stats.vercel.app/api?username=RamvilasRV&show_icons=true&theme=radical)](https://github.com/ramvilasrv)
