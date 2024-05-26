Let's manually translate the content into English while maintaining the markdown structure. Here is the translated content:

```markdown
# TyAdmin: Django based Models **No Code** zero-code, zero-learning cost management backend front-end generation tool, driven by Django Restful Framework and Ant Design Pro V4

![](https://img.shields.io/pypi/v/tyadmin-api-cli)
![](https://img.shields.io/pypi/wheel/tyadmin-api-cli)

Supports Python3.9! Unlimited Django version support, supports the latest Django4! Supports Django3!

# 🎬 Online Demo

> Account: tyadmin Password: tyadmin

~~Demo Address: https://tyadmin.funpython.cn/xadmin~~

**No Code!!! Without writing a single line of code, you can have a modernized backend management. Please give it a star, thank you!!**

TyAdmin: You only need five minutes to read the README to get started quickly. No additional documentation, no framework learning cost, and no need to write a single line of code. An entirely automated backend that you deserve!

# ✨ Features

- Automatically generates front-end and back-end management systems, with magical automatic interface connections. Login authentication, password modification, and Dashboard data statistics.
- Offers **CRUD, filtering, searching, full data export, selective export**
- **Foreign key fields, many-to-many fields, rich text, files, images, and Django's built-in permission system**

You only need to design the Model, configure which models need to be generated in settings, and run the command: [Get Started Quickly](#Get-Started-Quickly)

> The backend generates a Django app in the project directory, you just need to register it, no need to write a single line of code! The code is under your control, without hindering secondary development!
> The front-end generates an Ant Design Pro V4 project, you only need to start it once, no need to write a single line of code! The code is under your control, without hindering secondary development!

The front-end page, back-end interface, routes, and menus are all automatically connected. You only need to copy the documentation and modify the configuration without writing a single line of code!!

# 🎁 Built-in

## 1. Multiple login methods

![](http://cdn.pic.funpython.cn/blog_img/20201130234228.png)

## 2. Embedded automatic dashboard, automatically registers existing model count data.

![](http://cdn.pic.funpython.cn/blog_img/20201130234054.png)

## 3. Fully automatic list display, CRUD, filtering, searching, exporting to Excel

![](http://cdn.pic.funpython.cn/blog_img/20201130234448.png)
![](http://cdn.pic.funpython.cn/blog_img/20201130234525.png)

## 4. Supports Django's built-in permission groups, foreign key blue dot pop-up support

![](http://cdn.pic.funpython.cn/blog_img/20201130234705.png)
![](http://cdn.pic.funpython.cn/blog_img/20201130234753.png)

## 5. Automatic form field-level validation based on Model definitions

![](http://cdn.pic.funpython.cn/blog_img/20201010194705.png)

## 6. Embedded rich text support, you only need to define the field as `richTextField`, no additional integration is required.

![](http://cdn.pic.funpython.cn/blog_img/20201010192630.png)

# Get Started Quickly 🤟 

📨 Interactive feedback QQ group: 304094780

> Existing projects can start from step two, remember to modify the GEN_APPS variable to the list of apps you need to generate.
> If you have any questions, you can compare with the tyadmin_demo_finish project under demos to find the differences and check the [QA section](#QA-section)

## 1. Download the demo project and install dependencies (Note!! Existing projects do not need to download the demo project and can start from step two, remember to modify the GEN_APPS variable to the list of apps you need to generate)

```
git clone https://github.com/mtianyan/tyadmin_api_cli.git
cd tyadmin_api_cli/demos/tyadmin_demo_init
# Install the dependencies originally required by the project
pip install -r requirement.txt
```

## 2. Install tyadmin-api-cli and register tyadmin-api...

## Additional Features

- Dropdown multi-select menu or transfer box generated for ManyField
![](http://cdn.pic.funpython.cn/blog_img/20201202214922.png)
![](http://cdn.pic.funpython.cn/blog_img/20201202214936.png)
![](http://cdn.pic.funpython.cn/blog_img/20201202214957.png)

- RichTextField automatically generates rich text
```
detail = richTextField(verbose_name="Course Details")
```
![](http://cdn.pic.funpython.cn/blog_img/20201010193352.png)

- CharField and IntegerField choices automatically generate dropdown selection box on the form front-end.
```python
GENDER_CHOICES = (
   ("male", "Male"),
   ("female", "Female")
)
gender = CharField(verbose_name="Gender",choices=GENDER_CHOICES)
```
![](http://cdn.pic.funpython.cn/blog_img/20201010190635.png)

- ImageField automatically generates form upload function with preview, two display modes can be selected on the list page.
```python
avatar = ImageField(verbose_name="Avatar") # Variable name as avatar or logo will automatically be styled as an avatar
image = ImageField(verbose_name="Cover Image")
```
![](http://cdn.pic.funpython.cn/blog_img/20201010191641.png)
![](http://cdn.pic.funpython.cn/blog_img/20201010191917.png)
![](http://cdn.pic.funpython.cn/blog_img/20201010191843.png)

- FileField field generates file upload function.
```
download = FileField(verbose_name="Resource File")
```
![](http://cdn.pic.funpython.cn/blog_img/20201010193041.png)

- TextField automatically generates a front-end TextArea box
```python
desc = TextField(verbose_name="Course Description")
```
![](http://cdn.pic.funpython.cn/blog_img/20201010192813.png)

- BooleanField automatically generates a front-end Boolean radio button
```python
is_banner = BooleanField(verbose_name="Is Carousel")
```
![](http://cdn.pic.funpython.cn/blog_img/20201010193001.png)

- IntegerField automatically generates an Int input box on the front end
```
learn_times = IntegerField(verbose_name="Learning Duration (minutes)")
```
![](http://cdn.pic.funpython.cn/blog_img/20201010193445.png)

- DateField automatically generates a Date selection box on the front end
```
birthday = DateField(verbose_name="Birthday")
```
![](http://cdn.pic.funpython.cn/blog_img/20201010193614.png)

- DateTimeField automatically generates a form DateTime selection box, time range filter.
```
last_login = DateTimeField(verbose_name="Last Login")
```
![](http://cdn.pic.funpython.cn/blog_img/20201010193852.png)

> Note that those set with default and auto_now will not appear in the form
![](http://cdn.pic.funpython.cn/blog_img/20201010195116.png)
```

Now, I will save this translated content into a new markdown file for you to download.

The translated markdown file has been created. You can download it using the link below:

[Download Translated README.md](sandbox:/mnt/data/README_translated.md)