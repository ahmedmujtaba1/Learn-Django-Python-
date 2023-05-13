
<p> Let’s write the first view. Open the file polls/views.py and put the following Python code in it: </p>
<h3> from django.http import HttpResponse


def index(request):<br>
&#10240; &#10240; return HttpResponse("Hello, world. You're at the polls index.")
</h3>

<p>In the polls/urls.py file include the following code: </p>

<h3>
from django.urls import path

from . import views

urlpatterns = [ <br>
&#10240; &#10240; &#10240; path("", views.index, name="index"),
<br>]
