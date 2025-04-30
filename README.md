project:
  name: "🔥 BookStoreMVC"
  emoji: "📚🚀"
  tagline: "نظام مكتبة أونلاين خرافي باستخدام ASP.NET Core MVC 🔥"
  description: |
    BookStoreMVC هو مشروع ويب احترافي تم تطويره باستخدام ASP.NET Core MVC، بيحاكي مكتبة إلكترونية كاملة بإمكانيات عالية الجودة!
    بيديك تجربة مستخدم ممتازة لعرض، إضافة، تعديل، وحذف الكتب، مع دعم رفع صور الغلاف وتخزينها محليًا.
    التصميم مودرن، سريع، ومتجاوب، ومبني بأسلوب برمجي نظيف وجاهز للتطوير والتوسّع.

  features:
    - 🖼️ رفع صور الغلاف وتخزينها تلقائيًا داخل `wwwroot/images`
    - 🔍 صفحة تفاصيل لكل كتاب بتعرض الصورة والمعلومات
    - ➕ إضافة كتب جديدة عن طريق فورم سهل وبسيط
    - 🛠️ تعديل بيانات الكتب مع إمكانية تغيير الصورة
    - 🗑️ حذف الكتب مع تأكيد قبل الإجراء
    - 📱 تصميم متجاوب بيدعم الموبايل والتابلت
    - 💬 هيدر تنقل بين الصفحات، مع بحث سريع داخل الصفحة
    - 🧠 مبني بـ Entity Framework Core (Code First + Migrations)
    - 💾 قاعدة بيانات SQL Server LocalDB
    - 🛡️ حماية من overposting و CSRF

  technologies:
    backend:
      - ASP.NET Core MVC
      - Entity Framework Core
      - C#
    frontend:
      - HTML5
      - CSS3
      - Bootstrap 5
      - Razor Views
    database:
      - SQL Server LocalDB

  screenshots:
    - name: "📖 الصفحة الرئيسية"
      url: "https://via.placeholder.com/400x300.png?text=Index+Page"
    - name: "🔎 صفحة التفاصيل"
      url: "https://via.placeholder.com/400x300.png?text=Details+Page"
    - name: "➕ إضافة كتاب"
      url: "https://via.placeholder.com/400x300.png?text=Create+Page"
    - name: "🛠️ تعديل كتاب"
      url: "https://via.placeholder.com/400x300.png?text=Edit+Page"

  setup:
    prerequisites:
      - "✅ Visual Studio 2022"
      - "✅ .NET 6.0 أو أعلى"
      - "✅ SQL Server Express أو LocalDB"
    steps: |
      1. كلون المشروع:
         git clone https://github.com/your-username/BookStoreMVC.git

      2. افتح المشروع من Visual Studio

      3. افتح Package Manager Console ونفّذ:
         Update-Database

      4. شغّل المشروع:
         https://localhost:xxxx/Books

      5. استمتع بتجربة مكتبة فخمة جدًا 😎

  contributors:
    - name: "فادي أشرف"
      role: "Backend Developer 👨‍💻"
      bio: "مسؤول عن ربط الـ Entity Framework، تصميم الـ Controllers، ورفع الصور"

    - name: "مريم ربيعي"
      role: "Frontend Queen 💅"
      bio: "مصممة الواجهات، منظمة الـ Views، ومهندسة التنسيق المرئي"

  acknowledgements:
    - "شكر خاص لكل من ساهم في ظهور المشروع بالشكل الأسطوري ده 💥"
    - "لو المشروع عجبك، متنساش تعمله ⭐ على GitHub وتشاركه مع زملائك 👏"

  license: MIT
  version: 1.0.0
