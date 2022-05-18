# timer
scheduled timers

```python
class Task:
	def __init__(self, name, seconds):
		self.name = name
		self.seconds = seconds

class Timer:
	def __init__(self):
		self.tasks = []
	def add_tasks(self, task):
		self.tasks.append(task)
	def execute_tasks(self):
		for task in self.tasks:
			pass

timer = Timer()

timer.add_task(Task('Find', 30))
# ...
timer.add_task(Task('Follow', 30))

timer.execute_tasks()
```
