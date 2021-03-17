from django.contrib import admin

from .models import Post, Comment


admin.site.register(Post)
admin.site.register(Comment) 
@@ -0,0 +1,5 @@
from django.apps import AppConfig


class BlogConfig(AppConfig):
    name = 'blog'
