```python
class README:
    def __init__(self):
        self.username = "uto"
        self.age = "13"
        self.about = """im uto. a 13 year old self-taught developer, my interests include programming, gaming, typing, basketball, and "old"-retro stuff. 
        my favourite programming languages are rust, python & c#.
        im best at c#, and python. i also like writing/typing (essays, poems, etc) and reading is also something i like to do
        """
        
        self.links = "https://guns.lol/elo","https://uto.pages.dev", "https://gitlab.com/utoshu", "https://steamcommunity.com/id/utoshu"
       

    def show_info(self):
        print("name =", self.username)
        print("age =", self.age)
        print("about =", self.about)
        print("external links = ", self.links)
        
         
def main():
    readme = README()
    readme.show_info()
    
if __name__ == "__main__":
    main()
```
