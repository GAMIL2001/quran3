#استدعاء المكاتب
from pywebio import *
from pywebio.input import *
from pywebio.output import*
from pywebio import start_server
from pywebio import config
css="""
@import url('https://fonts.googleapis.com/css2?family=Amiri:wght@700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Amiri:wght@700&family=Aref+Ruqaa:wght@700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Amiri:wght@700&family=Aref+Ruqaa:wght@700&family=Reem+Kufi+Ink&display=swap');

#h3{
font-family: 'Amiri', serif;
color:blue;
}
#para{
font-family: 'Amiri', serif;
color:green;
}
#y{
font-family: 'Amiri', serif;
}
"""
@config(css_style=css)
def app():
    put_image('https://i.ytimg.com/vi/h2HsTJ5n1hM/maxresdefault.jpg', width= '800px' , height='480px')
    
    put_html("""
    <h3 id='h3'>تطبيق بالقران نحيا</h3>
    <p id= 'para' >اهلا بكم في موقع سماع القرآن الكريم بصوت منصور السالمي</p>
    <ul>
             
             <li>تدبر القرآن</li>
             <li> مواعظ وخطب</li>
             <li>احاديث وسيرة نبوية</li>
    </ul>    
    <details id='y' >
        <summary>الاستماع الى القران الكريم سورى الفاتحة والبقرة</summary>
        <p>سورة الفاتحة والبقرة بصوت منصور السالمي</p>
        <audio controls>
             <source src="https://ia601606.us.archive.org/5/items/mansour-al-salmi-full-quran-hd-mp-3-files/001.mp3" type= "audio/mp3">
        </audio>          
             <audio controls>
             <source src="https://ia601606.us.archive.org/5/items/mansour-al-salmi-full-quran-hd-mp-3-files/002.mp3" type= "audio/mp3">
        </audio>          
    </details>           
             <details id='y' >
        <summary>الاستماع الى القران الكريم سورة الرحمن ويوسف</summary>
        <p>سورة الرحمن ويوسف بصوت منصور السالمي</p>
        <audio controls>
             <source src="https://ia601606.us.archive.org/5/items/mansour-al-salmi-full-quran-hd-mp-3-files/055.mp3" type= "audio/mp3">
        </audio>          
             <audio controls>
             <source src="https://ia601606.us.archive.org/5/items/mansour-al-salmi-full-quran-hd-mp-3-files/012.mp3" type= "audio/mp3">
        </audio>          
    </details>     
    <hr>    
    <p> جميع الحقوق محفوظة لجميل بغدادي   </p>                       
""").style('direction:rtl; text-align:right;')
start_server(app,port=34345 , debug=True)
