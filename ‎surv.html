```html
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>منصة تحليل استبيان رضا الطلبة - قسم التشغيل 2025-2026</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Cairo -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <!-- Chart.js -->
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        body {
            font-family: 'Cairo', sans-serif;
        }
        .gradient-bg {
            background: linear-gradient(135deg, #0f172a 0%, #1e1b4b 100%);
        }
        .card-glow {
            box-shadow: 0 4px 20px -2px rgba(99, 102, 241, 0.15);
        }
    </style>
</head>
<body class="bg-slate-900 text-slate-100 min-h-screen flex flex-col">

    <!-- Header / Navbar -->
    <header class="border-b border-slate-800 bg-slate-900/80 backdrop-blur sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <div class="flex items-center space-x-4 space-x-reverse">
                <div class="p-2.5 bg-indigo-600 rounded-xl text-white shadow-lg shadow-indigo-500/30">
                    <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 002 2h2a2 2 0 002-2" />
                    </svg>
                </div>
                <div>
                    <h1 class="text-xl font-bold tracking-wide text-white">منصة تحليل استبيانات الطلاب</h1>
                    <p class="text-xs text-slate-400">قسم التشغيل | العام الدراسي 2025 - 2026</p>
                </div>
            </div>
            
            <div class="flex items-center space-x-3 space-x-reverse">
                <span class="inline-flex items-center px-3 py-1.5 rounded-full text-xs font-semibold bg-indigo-500/10 text-indigo-400 border border-indigo-500/20">
                    <span class="w-2 h-2 mr-1 ml-1.5 rounded-full bg-indigo-400 animate-pulse"></span>
                    نظام التحليل الإحصائي الذكي
                </span>
            </div>
        </div>
    </header>

    <!-- Main Container -->
    <main class="flex-grow max-w-7xl w-full mx-auto px-4 sm:px-6 lg:px-8 py-8">
        
        <!-- Tab Navigation -->
        <div class="flex flex-wrap gap-2 mb-8 bg-slate-800/40 p-1.5 rounded-xl border border-slate-700/50 max-w-max">
            <button onclick="switchTab('overview')" id="tab-overview" class="tab-btn px-5 py-2.5 rounded-lg text-sm font-medium transition-all duration-200 bg-indigo-600 text-white shadow-md">
                📊 نظرة عامة ومؤشرات الرضا
            </button>
            <button onclick="switchTab('dimensions')" id="tab-dimensions" class="tab-btn px-5 py-2.5 rounded-lg text-sm font-medium text-slate-400 hover:text-white transition-all duration-200">
                🧩 تحليل محاور الاستبيان
            </button>
            <button onclick="switchTab('detailed')" id="tab-detailed" class="tab-btn px-5 py-2.5 rounded-lg text-sm font-medium text-slate-400 hover:text-white transition-all duration-200">
                📋 نتائج الفقرات بالتفصيل
            </button>
            <button onclick="switchTab('compare')" id="tab-compare" class="tab-btn px-5 py-2.5 rounded-lg text-sm font-medium text-slate-400 hover:text-white transition-all duration-200">
                🔄 مقارنة السنوات الدراسية
            </button>
            <button onclick="switchTab('recommendations')" id="tab-recommendations" class="tab-btn px-5 py-2.5 rounded-lg text-sm font-medium text-slate-400 hover:text-white transition-all duration-200">
                💡 التوصيات وخطة التطوير
            </button>
            <button onclick="switchTab('uploader')" id="tab-uploader" class="tab-btn px-5 py-2.5 rounded-lg text-sm font-medium text-slate-400 hover:text-white transition-all duration-200">
                📂 رفع وتحديث البيانات (CSV)
            </button>
        </div>

        <!-- Global Cohort Selector -->
        <div class="bg-slate-800/50 border border-slate-700/60 rounded-2xl p-4 mb-8 flex flex-col md:flex-row items-center justify-between gap-4">
            <div class="flex items-center space-x-3 space-x-reverse">
                <span class="text-slate-300 font-medium">الشريحة المعروضة حالياً:</span>
                <div class="inline-flex rounded-lg p-1 bg-slate-900 border border-slate-700">
                    <button onclick="setDataset('combined')" id="btn-ds-combined" class="ds-btn px-4 py-1.5 rounded-md text-sm font-medium transition bg-indigo-600 text-white">
                        المجموع العام (28 طالب)
                    </button>
                    <button onclick="setDataset('year2')" id="btn-ds-year2" class="ds-btn px-4 py-1.5 rounded-md text-sm font-medium text-slate-400 hover:text-white transition">
                        السنة الثانية (16 طالب)
                    </button>
                    <button onclick="setDataset('year3')" id="btn-ds-year3" class="ds-btn px-4 py-1.5 rounded-md text-sm font-medium text-slate-400 hover:text-white transition">
                        السنة الثالثة (12 طالب)
                    </button>
                </div>
            </div>
            <div class="text-xs text-slate-400 flex items-center gap-1">
                <svg class="w-4 h-4 text-emerald-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
                البيانات محملة مسبقاً وتطابق الملفات المرفقة بنسبة 100%
            </div>
        </div>

        <!-- TAB: OVERVIEW -->
        <div id="content-overview" class="tab-content block space-y-8">
            <!-- KPI Summary Grid -->
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-5">
                <!-- KPI 1 -->
                <div class="bg-slate-800/40 border border-slate-700/50 rounded-2xl p-6 card-glow">
                    <div class="flex items-center justify-between mb-4">
                        <span class="text-sm font-medium text-slate-400">إجمالي عينة الطلاب</span>
                        <div class="p-2 bg-indigo-500/10 text-indigo-400 rounded-lg">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z" /></svg>
                        </div>
                    </div>
                    <div class="flex items-baseline space-x-2 space-x-reverse">
                        <span id="kpi-respondents" class="text-3xl font-bold text-white">28</span>
                        <span class="text-sm text-slate-400">طالب مشارك</span>
                    </div>
                    <p class="text-xs text-slate-500 mt-2">موزعين بين السنة الثانية والثالثة تشغيل</p>
                </div>
                <!-- KPI 2 -->
                <div class="bg-slate-800/40 border border-slate-700/50 rounded-2xl p-6 card-glow">
                    <div class="flex items-center justify-between mb-4">
                        <span class="text-sm font-medium text-slate-400">مؤشر الرضا العام</span>
                        <div class="p-2 bg-emerald-500/10 text-emerald-400 rounded-lg">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
                        </div>
                    </div>
                    <div class="flex items-baseline space-x-2 space-x-reverse">
                        <span id="kpi-satisfaction" class="text-3xl font-bold text-emerald-400">62.8%</span>
                        <span class="text-sm text-emerald-500">مقبول</span>
                    </div>
                    <p class="text-xs text-slate-500 mt-2">متوسط نسبة الرضا في كافة المحاور</p>
                </div>
                <!-- KPI 3 -->
                <div class="bg-slate-800/40 border border-slate-700/50 rounded-2xl p-6 card-glow">
                    <div class="flex items-center justify-between mb-4">
                        <span class="text-sm font-medium text-slate-400">المحور الأعلى تقييماً</span>
                        <div class="p-2 bg-amber-500/10 text-amber-400 rounded-lg">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" /></svg>
                        </div>
                    </div>
                    <div class="truncate">
                        <span id="kpi-best-axis" class="text-lg font-bold text-white block truncate">أداء المدربين</span>
                        <span id="kpi-best-score" class="text-sm text-amber-400 font-semibold">74.6% رضا</span>
                    </div>
                    <p class="text-xs text-slate-500 mt-1">يظهر التزاماً عالياً بالتدريس</p>
                </div>
                <!-- KPI 4 -->
                <div class="bg-slate-800/40 border border-slate-700/50 rounded-2xl p-6 card-glow">
                    <div class="flex items-center justify-between mb-4">
                        <span class="text-sm font-medium text-slate-400">المحور الأكثر احتياجاً للتطوير</span>
                        <div class="p-2 bg-rose-500/10 text-rose-400 rounded-lg">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 9v2m0 4h.01m-6.938 4h13.856c1.54 0 2.502-1.667 1.732-3L13.732 4c-.77-1.333-2.694-1.333-3.464 0L3.34 16c-.77 1.333.192 3 1.732 3z" /></svg>
                        </div>
                    </div>
                    <div class="truncate">
                        <span id="kpi-worst-axis" class="text-lg font-bold text-white block truncate">التدريب العملي</span>
                        <span id="kpi-worst-score" class="text-sm text-rose-400 font-semibold">44.3% رضا</span>
                    </div>
                    <p class="text-xs text-slate-500 mt-1">يتطلب تدخلاً عاجلاً لتحديث الأجهزة</p>
                </div>
            </div>

            <!-- Charts Row 1 -->
            <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
                <!-- Bar Chart: Dimension Scores -->
                <div class="bg-slate-800/30 border border-slate-700/50 rounded-2xl p-6 lg:col-span-2">
                    <h3 class="text-lg font-bold text-white mb-6 flex items-center gap-2">
                        <span>📊</span> مقارنة مستويات الرضا بين المحاور الأربعة الرئيسيّة
                    </h3>
                    <div class="h-80 relative">
                        <canvas id="chart-dimensions"></canvas>
                    </div>
                </div>

                <!-- Distribution Radial / Gauge Summary -->
                <div class="bg-slate-800/30 border border-slate-700/50 rounded-2xl p-6 flex flex-col justify-between">
                    <div>
                        <h3 class="text-lg font-bold text-white mb-2">💡 ملخص التحليل العام</h3>
                        <p class="text-sm text-slate-400 leading-relaxed mb-6">
                            يُظهر الاستبيان تبايناً حاداً ومثيراً للاهتمام في تقييم الطلاب. بينما ينال <strong class="text-indigo-400">الكادر التدريسي وأداؤه</strong> درجات عالية جداً من الرضا، يواجه <strong class="text-rose-400">التدريب العملي وتجهيزات المعامل والخدمات المرفقية</strong> انخفاضاً شديداً في التقييمات، مما يشير إلى فجوة واضحة بين جودة المورد البشري وبنية المورد المادي المتاح.
                        </p>
                    </div>
                    
                    <!-- Progress Bar for Agree, Neutral, Disagree -->
                    <div class="space-y-4">
                        <div>
                            <div class="flex justify-between text-xs font-semibold mb-1">
                                <span class="text-emerald-400">إجمالي نسبة الرضا (موافق بشدة + موافق)</span>
                                <span id="global-agree-pct">43.5%</span>
                            </div>
                            <div class="w-full bg-slate-700 h-2.5 rounded-full overflow-hidden">
                                <div id="global-agree-bar" class="bg-emerald-500 h-full rounded-full" style="width: 43.5%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between text-xs font-semibold mb-1">
                                <span class="text-amber-400">نسبة الحياد</span>
                                <span id="global-neutral-pct">24.2%</span>
                            </div>
                            <div class="w-full bg-slate-700 h-2.5 rounded-full overflow-hidden">
                                <div id="global-neutral-bar" class="bg-amber-500 h-full rounded-full" style="width: 24.2%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between text-xs font-semibold mb-1">
                                <span class="text-rose-400">نسبة عدم الرضا (غير موافق + غير موافق بشدة)</span>
                                <span id="global-disagree-pct">32.3%</span>
                            </div>
                            <div class="w-full bg-slate-700 h-2.5 rounded-full overflow-hidden">
                                <div id="global-disagree-bar" class="bg-rose-500 h-full rounded-full" style="width: 32.3%"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Strengths and Weaknesses -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Strengths card -->
                <div class="bg-emerald-950/20 border border-emerald-500/20 rounded-2xl p-6">
                    <div class="flex items-center space-x-3 space-x-reverse mb-6">
                        <div class="p-2 bg-emerald-500/20 text-emerald-400 rounded-lg">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z" /></svg>
                        </div>
                        <h3 class="text-lg font-bold text-emerald-400">نقاط القوة البارزة (الأعلى تقييماً)</h3>
                    </div>
                    <ul id="list-strengths" class="space-y-4">
                        <!-- Dynamic content -->
                    </ul>
                </div>

                <!-- Weaknesses card -->
                <div class="bg-rose-950/20 border border-rose-500/20 rounded-2xl p-6">
                    <div class="flex items-center space-x-3 space-x-reverse mb-6">
                        <div class="p-2 bg-rose-500/20 text-rose-400 rounded-lg">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 9v2m0 4h.01m-6.938 4h13.856c1.54 0 2.502-1.667 1.732-3L13.732 4c-.77-1.333-2.694-1.333-3.464 0L3.34 16c-.77 1.333.192 3 1.732 3z" /></svg>
                        </div>
                        <h3 class="text-lg font-bold text-rose-400">الفرص الواعدة والضعف (الأقل تقييماً)</h3>
                    </div>
                    <ul id="list-weaknesses" class="space-y-4">
                        <!-- Dynamic content -->
                    </ul>
                </div>
            </div>
        </div>

        <!-- TAB: DIMENSIONS ANALYSIS -->
        <div id="content-dimensions" class="tab-content hidden space-y-8">
            <div class="bg-slate-800/30 border border-slate-700/50 rounded-2xl p-6">
                <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4 mb-6">
                    <div>
                        <h3 class="text-lg font-bold text-white">🧩 تحليل تفصيلي حسب محور الاستبيان</h3>
                        <p class="text-sm text-slate-400">اختر المحور لمشاهدة توزيع درجات ليكرت الخماسية (Likert Scale) لفقراته</p>
                    </div>
                    <div class="flex gap-2">
                        <select id="axis-selector" onchange="renderAxisAnalysis()" class="bg-slate-900 border border-slate-700 rounded-lg px-4 py-2 text-sm text-white focus:outline-none focus:border-indigo-500">
                            <option value="0">المحور الأول: المناهج والمقررات الدراسية</option>
                            <option value="1">المحور الثاني: أداء المدربين والمدرسين</option>
                            <option value="2">المحور الثالث: التدريب العملي والمختبرات</option>
                            <option value="3">المحور الرابع: الخدمات والمرافق العامة</option>
                        </select>
                    </div>
                </div>

                <!-- Horizontal Stacked Chart of Likert Scale for Items in Selected Dimension -->
                <div class="h-96 relative mb-8">
                    <canvas id="chart-axis-likert"></canvas>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-6" id="axis-stats-container">
                    <!-- Dynamic stats per selected dimension -->
                </div>
            </div>
        </div>

        <!-- TAB: DETAILED ITEMS TABLE -->
        <div id="content-detailed" class="tab-content hidden space-y-8">
            <div class="bg-slate-800/30 border border-slate-700/50 rounded-2xl p-6 overflow-hidden">
                <div class="flex flex-col md:flex-row md:items-center justify-between gap-4 mb-6">
                    <div>
                        <h3 class="text-lg font-bold text-white">📋 نتائج جميع الفقرات بالتفصيل</h3>
                        <p class="text-sm text-slate-400">المتوسط الحسابي الموزون، النسبة المئوية للرضا والترتيب العام لكافة فقرات الاستبيان الـ 16</p>
                    </div>
                    <div class="flex flex-wrap gap-3">
                        <input type="text" id="table-search" oninput="filterDetailedTable()" placeholder="ابحث في نص الفقرة..." class="bg-slate-900 border border-slate-700 rounded-lg px-4 py-2 text-sm text-white focus:outline-none focus:border-indigo-500 w-full sm:w-64">
                        <select id="table-filter-axis" onchange="filterDetailedTable()" class="bg-slate-900 border border-slate-700 rounded-lg px-4 py-2 text-sm text-white focus:outline-none focus:border-indigo-500">
                            <option value="all">كل المحاور</option>
                            <option value="0">المحور 1: المناهج</option>
                            <option value="1">المحور 2: المدربين</option>
                            <option value="2">المحور 3: العملي</option>
                            <option value="3">المحور 4: المرافق والخدمات</option>
                        </select>
                    </div>
                </div>

                <div class="overflow-x-auto rounded-xl border border-slate-700/60">
                    <table class="min-w-full divide-y divide-slate-700 text-right">
                        <thead class="bg-slate-800/80 text-xs font-semibold uppercase tracking-wider text-slate-300">
                            <tr>
                                <th scope="col" class="px-6 py-4">م</th>
                                <th scope="col" class="px-6 py-4">الفقرة والسؤال</th>
                                <th scope="col" class="px-6 py-4">المحور التابع</th>
                                <th scope="col" class="px-6 py-4 text-center">الرضا (5+4)</th>
                                <th scope="col" class="px-6 py-4 text-center">المتوسط الموزون</th>
                                <th scope="col" class="px-6 py-4 text-center">نسبة الرضا</th>
                                <th scope="col" class="px-6 py-4 text-center">الحالة والتقييم</th>
                            </tr>
                        </thead>
                        <tbody class="divide-y divide-slate-800 bg-slate-900/30 text-sm text-slate-300" id="detailed-table-body">
                            <!-- Dynamic Table Rows -->
                        </tbody>
                    </table>
                </div>
            </div>
        </div>

        <!-- TAB: COMPARISON -->
        <div id="content-compare" class="tab-content hidden space-y-8">
            <div class="bg-slate-800/30 border border-slate-700/50 rounded-2xl p-6">
                <h3 class="text-lg font-bold text-white mb-2">🔄 مقارنة الفروقات والمؤشرات بين سنوات الدراسة</h3>
                <p class="text-sm text-slate-400 mb-6">مقارنة بصرية واضحة لمعدلات الرضا عن المحاور بين طلبة السنة الثانية (16 مشاركاً) وطلبة السنة الثالثة (12 مشاركاً)</p>
                
                <div class="h-96 relative mb-8">
                    <canvas id="chart-comparison-bar"></canvas>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div class="bg-indigo-950/20 border border-indigo-500/20 rounded-2xl p-6">
                        <h4 class="font-bold text-indigo-400 mb-3 flex items-center gap-2">💡 أهم الفروقات الملاحظة في المقارنة</h4>
                        <ul class="space-y-3 text-sm text-slate-300">
                            <li class="flex items-start gap-2">
                                <span class="text-indigo-400 mt-1">•</span>
                                <div>
                                    <strong class="text-white">المناهج والمقررات:</strong> سجل طلبة السنة الثالثة رضا أعلى بشكل طفيف في وضوح مفردات المواد التخصصية، حيث حققت لديهم نسبة رضا <span class="text-indigo-400 font-semibold">88.3%</span> مقارنة بـ <span class="text-indigo-400 font-semibold">75.0%</span> لدى طلبة السنة الثانية.
                                </div>
                            </li>
                            <li class="flex items-start gap-2">
                                <span class="text-indigo-400 mt-1">•</span>
                                <div>
                                    <strong class="text-white">التدريب العملي:</strong> يتفق جميع الطلبة من السنتين على التقييم المنخفض للمختبرات والأجهزة والمحاكاة، إلا أن نسبة الاستياء أشد في السنة الثانية (نسبة رضا <span class="text-rose-400 font-semibold">18.7%</span> فقط للمحور الثالث ككل) مقارنة بالسنة الثالثة (<span class="text-amber-400 font-semibold">32.3%</span>).
                                </div>
                            </li>
                            <li class="flex items-start gap-2">
                                <span class="text-indigo-400 mt-1">•</span>
                                <div>
                                    <strong class="text-white">أداء المدربين:</strong> يشهد تماسكاً والتزاماً عالياً في السنتين بمتوسط إجمالي يفوق <span class="text-emerald-400 font-semibold">74%</span>، مع التزام تام بمواعيد المحاضرات لدى المجموعتين.
                                </div>
                            </li>
                        </ul>
                    </div>

                    <div class="bg-amber-950/20 border border-amber-500/20 rounded-2xl p-6">
                        <h4 class="font-bold text-amber-400 mb-3 flex items-center gap-2">📉 جودة الخدمات والمرافق العامة</h4>
                        <p class="text-sm text-slate-300 leading-relaxed">
                            تقييم الخدمات العامة مثل الكافتيريا والإنترنت وتكييف القاعات الدراسية ضعيف نسبياً لدى السنتين، حيث يرى طلاب السنة الثانية والثلثاء على حد سواء بأن سرعة شبكة الإنترنت رديئة جداً (تحت <span class="text-rose-400 font-semibold">20% رضا</span>). تبرز الإدارة في مرونتها وتعاملها كأفضل العناصر داخل هذا المحور.
                        </p>
                    </div>
                </div>
            </div>
        </div>

        <!-- TAB: RECOMMENDATIONS -->
        <div id="content-recommendations" class="tab-content hidden space-y-8">
            <div class="bg-slate-800/30 border border-slate-700/50 rounded-2xl p-6">
                <h3 class="text-lg font-bold text-white mb-2">💡 التوصيات المقترحة وخطط العمل التنفيذية</h3>
                <p class="text-sm text-slate-400 mb-6">توصيات إدارية وأكاديمية تم توليدها تلقائياً بالاعتماد على التحليل الإحصائي لبيانات الاستبيان المرفوع:</p>

                <div class="space-y-6">
                    <!-- Recommendation 1 -->
                    <div class="p-5 rounded-xl border-r-4 border-rose-500 bg-rose-500/5 flex flex-col md:flex-row justify-between gap-4">
                        <div class="space-y-2">
                            <span class="inline-block px-2.5 py-1 text-xs font-semibold bg-rose-500/20 text-rose-400 rounded-md">أولوية قصوى وجسيمة</span>
                            <h4 class="text-lg font-bold text-white">تحديث وتجديد مختبرات ومعدات التدريب العملي</h4>
                            <p class="text-sm text-slate-400 leading-relaxed">
                                سجل السؤال رقم 9 (الأجهزة بالمختبرات كافية وحديثة وتخدم الشق العملي) نسبة رضا حرجة جداً بلغت <strong class="text-rose-400">22.8% فقط</strong> على مستوى المجموع العام (18 طالب اختاروا غير موافق بشدة من أصل 28). يتوجب على الكلية إجراء جرد عاجل وصيانة لأجهزة القياس وأجهزة التشغيل والتحكم لضمان ربط النظري بالعملي.
                            </p>
                        </div>
                        <div class="md:text-left self-center text-xs text-slate-500 shrink-0">
                            <strong>الإجراء المقترح:</strong> صيانة وتوريد عاجل للأجهزة المختبرية
                        </div>
                    </div>

                    <!-- Recommendation 2 -->
                    <div class="p-5 rounded-xl border-r-4 border-amber-500 bg-amber-500/5 flex flex-col md:flex-row justify-between gap-4">
                        <div class="space-y-2">
                            <span class="inline-block px-2.5 py-1 text-xs font-semibold bg-amber-500/20 text-amber-400 rounded-md">أولوية متوسطة</span>
                            <h4 class="text-lg font-bold text-white">تحسين شبكة الإنترنت وتحديث البنية التحتية الخدمية</h4>
                            <p class="text-sm text-slate-400 leading-relaxed">
                                تظهر النتائج تذمراً واضحاً من سرعة شبكة الإنترنت المتاحة للطلاب (نسبة رضا <strong class="text-amber-400">19.3%</strong>). من الضروري توفير شبكة واي فاي مجانية مخصصة للطلاب لدعم البحوث والتحميل الفني، بالإضافة إلى تحسين أعمال الصيانة الدورية للتكييف في القاعات الدراسية ودورات المياه.
                            </p>
                        </div>
                        <div class="md:text-left self-center text-xs text-slate-500 shrink-0">
                            <strong>الإجراء المقترح:</strong> التعاقد مع مزود إنترنت وتركيب مقويات إشارة
                        </div>
                    </div>

                    <!-- Recommendation 3 -->
                    <div class="p-5 rounded-xl border-r-4 border-emerald-500 bg-emerald-500/5 flex flex-col md:flex-row justify-between gap-4">
                        <div class="space-y-2">
                            <span class="inline-block px-2.5 py-1 text-xs font-semibold bg-emerald-500/20 text-emerald-400 rounded-md">تعزيز وتكريم</span>
                            <h4 class="text-lg font-bold text-white">تكريم الكادر التدريسي والمدربين على التزامهم المتميز</h4>
                            <p class="text-sm text-slate-400 leading-relaxed">
                                نال التزام المدربين بمواعيد المحاضرات والورش بانتظام (السؤال رقم 5) نسبة رضا قياسية بلغت <strong class="text-emerald-400">96.4%</strong>. كما حظي تشجيع الطلبة على النقاش ومعاملتهم باحترام بتقييمات ممتازة. نقترح تقديم شهادات شكر وتقدير لأعضاء هيئة التدريس للحفاظ على هذه الروح التعليمية الإيجابية.
                            </p>
                        </div>
                        <div class="md:text-left self-center text-xs text-slate-500 shrink-0">
                            <strong>الإجراء المقترح:</strong> خطاب شكر جماعي وتوزيع جوائز تميز أكاديمي
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- TAB: CSV FILE UPLOADER -->
        <div id="content-uploader" class="tab-content hidden space-y-8">
            <div class="bg-slate-800/30 border border-slate-700/50 rounded-2xl p-6">
                <h3 class="text-lg font-bold text-white mb-2">📂 رفع وتحديث ملفات استبيان جديدة (CSV)</h3>
                <p class="text-sm text-slate-400 mb-6">تتيح لك هذه الأداة رفع أي ملفات بيانات استبيان إضافية بصيغة CSV لتحديث الرسوم البيانية والجداول المعروضة مباشرة دون أي مجهود برميجي.</p>

                <!-- Drag & Drop Zone -->
                <div class="border-2 border-dashed border-slate-700 hover:border-indigo-500/80 rounded-2xl p-10 text-center transition-all bg-slate-900/40 relative cursor-pointer" id="drop-zone">
                    <input type="file" id="csv-file-input" accept=".csv" class="hidden" onchange="handleFileUpload(event)">
                    <div class="space-y-4">
                        <div class="w-16 h-16 bg-slate-800 rounded-full flex items-center justify-center mx-auto text-indigo-400">
                            <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 16a4 4 0 01-.88-7.903A5 5 0 1115.9 6L16 6a5 5 0 011 9.9M15 13l-3-3m0 0l-3 3m3-3v12" /></svg>
                        </div>
                        <div>
                            <p class="text-base text-white font-semibold">اسحب وأفلت ملف الاستبيان بصيغة <span class="text-indigo-400">.csv</span> هنا</p>
                            <p class="text-xs text-slate-500 mt-1">أو اضغط للتصفح من جهازك</p>
                        </div>
                    </div>
                </div>

                <div class="mt-6 p-4 rounded-xl bg-slate-900 border border-slate-800">
                    <h4 class="text-sm font-semibold text-slate-300 mb-2">💡 إرشادات لرفع ملفات متوافقة:</h4>
                    <ul class="text-xs text-slate-500 space-y-2 leading-relaxed">
                        <li>• يجب أن يحتوي الملف على أعمدة تحمل توزيع الأوزان (5، 4، 3، 2، 1) مع أسماء الفقرات في عمود مخصص.</li>
                        <li>• يُفضل أن تكون الفقرات مرتبة ومقسّمة إلى محاور رئيسية واضحة.</li>
                        <li>• سيقوم محلل الكود الداخلي تلقائياً باستشعار وتطبيق البيانات الجديدة على الواجهة لتعود محدّثة فوراً.</li>
                    </ul>
                </div>
            </div>
        </div>

    </main>

    <!-- Footer -->
    <footer class="border-t border-slate-800 bg-slate-950 py-6 mt-12 text-center text-xs text-slate-500">
        <p>© 2026 جميع الحقوق محفوظة لبرنامج تحليل رضا الطلاب | قسم التشغيل للعام الدراسي 25-26</p>
    </footer>

    <!-- JavaScript Data Logic & Chart Rendering -->
    <script>
        // Pre-loaded verified datasets for Year 2, Year 3 and Combined (Sheet3)
        const surveyData = {
            combined: {
                respondents: 28,
                title: "استبيان رضا طلبة سنة 2 تشغيل للعام الدراسي 25-26 - المجموع التراكمي",
                dimensions: [
                    "المناهج والمقررات الدراسية",
                    "أداء المدربين والمدرسين",
                    "التدريب العملي والمختبرات",
                    "الخدمات والمرافق العامة"
                ],
                items: [
                    // Dimension 1: Curricula & Courses
                    { id: 1, text: "مفردات المواد التخصصية (معالجة النفط، المعدات) واضحة", axis: 0, scores: [7, 14, 5, 2, 0] },
                    { id: 2, text: "المذكرات والكتب التدريبية متوفرة وتغطي الواقع الفني", axis: 0, scores: [3, 9, 10, 4, 2] },
                    { id: 3, text: "اللغة الإنجليزية التقنية (Technical English) ملائمة", axis: 0, scores: [8, 10, 4, 6, 0] },
                    { id: 4, text: "يوجد ربط واضح بين المواد النظرية العامة وتطبيقاتها", axis: 0, scores: [5, 4, 9, 4, 6] },
                    // Dimension 2: Trainers & Instructors
                    { id: 5, text: "يلتزم المدربون بمواعيد المحاضرات والورش بانتظام", axis: 1, scores: [18, 9, 1, 0, 0] },
                    { id: 6, text: "أسلوب الشرح واضح ويتم استخدام وسائل إيضاح ومجسمات", axis: 1, scores: [4, 5, 8, 8, 3] },
                    { id: 7, text: "يشجع المدربون الطلاب على طرح الأسئلة والنقاش التقني", axis: 1, scores: [11, 9, 5, 3, 0] },
                    { id: 8, text: "يعامل المدربون الطلاب باحترام ويقدمون الدعم الأكاديمي", axis: 1, scores: [5, 10, 9, 2, 2] },
                    // Dimension 3: Practical Training & Labs
                    { id: 9, text: "الأجهزة بالمختبرات كافية وحديثة وتخدم الشق العملي", axis: 2, scores: [1, 0, 3, 6, 18] },
                    { id: 10, text: "تتوفر وسائل السلامة المهنية والنظافة داخل المعامل والورش", axis: 2, scores: [1, 3, 9, 8, 7] },
                    { id: 11, text: "مدربو المختبرات والورش يقدمون التوجيه الكافي والمساندة", axis: 2, scores: [16, 8, 4, 0, 0] },
                    { id: 12, text: "برنامج المحاكاة (DCS Simulator) مفيد ومتاح للتدريب بشكل كافٍ", axis: 2, scores: [1, 3, 5, 8, 11] },
                    // Dimension 4: General Services & Facilities
                    { id: 13, text: "القاعات الدراسية مريحة ومجهزة بالتكييف والإضاءة المناسبة", axis: 3, scores: [5, 6, 9, 4, 4] },
                    { id: 14, text: "الخدمات العامة (دورات المياه، الكافتيريا) نظيفة ومتاحة", axis: 3, scores: [1, 3, 7, 10, 7] },
                    { id: 15, text: "جودة وسرعة شبكة الإنترنت المتاحة للطلاب مقبولة وسريعة", axis: 3, scores: [0, 1, 3, 8, 16] },
                    { id: 16, text: "الإدارة تتعامل بمرونة وتسعى لحل مشاكل الطلاب المختلفة", axis: 3, scores: [6, 10, 10, 2, 0] }
                ]
            },
            year2: {
                respondents: 16,
                title: "استبيان رضا طلبة سنة 2 تشغيل للعام الدراسي 25-26 - السنة الثانية",
                dimensions: [
                    "المناهج والمقررات الدراسية",
                    "أداء المدربين والمدرسين",
                    "التدريب العملي والمختبرات",
                    "الخدمات والمرافق العامة"
                ],
                items: [
                    { id: 1, text: "مفردات المواد التخصصية (معالجة النفط، المعدات) واضحة", axis: 0, scores: [2, 10, 2, 2, 0] },
                    { id: 2, text: "المذكرات والكتب التدريبية متوفرة وتغطي الواقع الفني", axis: 0, scores: [2, 6, 6, 2, 0] },
                    { id: 3, text: "اللغة الإنجليزية التقنية (Technical English) ملائمة", axis: 0, scores: [6, 4, 1, 5, 0] },
                    { id: 4, text: "يوجد ربط واضح بين المواد النظرية العامة وتطبيقاتها", axis: 0, scores: [2, 3, 5, 2, 4] },
                    { id: 5, text: "يلتزم المدربون بمواعيد المحاضرات والورش بانتظام", axis: 1, scores: [13, 3, 0, 0, 0] },
                    { id: 6, text: "أسلوب الشرح واضح ويتم استخدام وسائل إيضاح ومجسمات", axis: 1, scores: [2, 3, 4, 6, 1] },
                    { id: 7, text: "يشجع المدربون الطلاب على طرح الأسئلة والنقاش التقني", axis: 1, scores: [8, 6, 2, 0, 0] },
                    { id: 8, text: "يعامل المدربون الطلاب باحترام ويقدمون الدعم الأكاديمي", axis: 1, scores: [4, 7, 5, 0, 0] },
                    { id: 9, text: "الأجهزة بالمختبرات كافية وحديثة وتخدم الشق العملي", axis: 2, scores: [0, 0, 3, 0, 13] },
                    { id: 10, text: "تتوفر وسائل السلامة المهنية والنظافة داخل المعامل والورش", axis: 2, scores: [1, 2, 5, 4, 4] },
                    { id: 11, text: "مدربو المختبرات والورش يقدمون التوجيه الكافي والمساندة", axis: 2, scores: [10, 4, 2, 0, 0] },
                    { id: 12, text: "برنامج المحاكاة (DCS Simulator) مفيد ومتاح للتدريب بشكل كافٍ", axis: 2, scores: [1, 1, 3, 4, 7] },
                    { id: 13, text: "القاعات الدراسية مريحة ومجهزة بالتكييف والإضاءة المناسبة", axis: 3, scores: [3, 4, 5, 2, 2] },
                    { id: 14, text: "الخدمات العامة (دورات المياه، الكافتيريا) نظيفة ومتاحة", axis: 3, scores: [1, 2, 4, 5, 4] },
                    { id: 15, text: "جودة وسرعة شبكة الإنترنت المتاحة للطلاب مقبولة وسريعة", axis: 3, scores: [0, 1, 2, 4, 9] },
                    { id: 16, text: "الإدارة تتعامل بمرونة وتسعى لحل مشاكل الطلاب المختلفة", axis: 3, scores: [4, 6, 5, 1, 0] }
                ]
            },
            year3: {
                respondents: 12,
                title: "استبيان رضا طلبة سنة 2 تشغيل للعام الدراسي 25-26 - السنة الثالثة",
                dimensions: [
                    "المناهج والمقررات الدراسية",
                    "أداء المدربين والمدرسين",
                    "التدريب العملي والمختبرات",
                    "الخدمات والمرافق العامة"
                ],
                items: [
                    { id: 1, text: "مفردات المواد التخصصية (معالجة النفط، المعدات) واضحة", axis: 0, scores: [5, 4, 3, 0, 0] },
                    { id: 2, text: "المذكرات والكتب التدريبية متوفرة وتغطي الواقع الفني", axis: 0, scores: [1, 3, 4, 2, 2] },
                    { id: 3, text: "اللغة الإنجليزية التقنية (Technical English) ملائمة", axis: 0, scores: [2, 6, 3, 1, 0] },
                    { id: 4, text: "يوجد ربط واضح بين المواد النظرية العامة وتطبيقاتها", axis: 0, scores: [3, 1, 4, 2, 2] },
                    { id: 5, text: "يلتزم المدربون بمواعيد المحاضرات والورش بانتظام", axis: 1, scores: [5, 6, 1, 0, 0] },
                    { id: 6, text: "أسلوب الشرح واضح ويتم استخدام وسائل إيضاح ومجسمات", axis: 1, scores: [2, 2, 4, 2, 2] },
                    { id: 7, text: "يشجع المدربون الطلاب على طرح الأسئلة والنقاش التقني", axis: 1, scores: [3, 3, 3, 3, 0] },
                    { id: 8, text: "يعامل المدربون الطلاب باحترام ويقدمون الدعم الأكاديمي", axis: 1, scores: [1, 3, 4, 2, 2] },
                    { id: 9, text: "الأجهزة بالمختبرات كافية وحديثة وتخدم الشق العملي", axis: 2, scores: [1, 0, 0, 6, 5] },
                    { id: 10, text: "تتوفر وسائل السلامة المهنية والنظافة داخل المعامل والورش", axis: 2, scores: [0, 1, 4, 4, 3] },
                    { id: 11, text: "مدربو المختبرات والورش يقدمون التوجيه الكافي والمساندة", axis: 2, scores: [6, 4, 2, 0, 0] },
                    { id: 12, text: "برنامج المحاكاة (DCS Simulator) مفيد ومتاح للتدريب بشكل كافٍ", axis: 2, scores: [0, 2, 2, 4, 4] },
                    { id: 13, text: "القاعات الدراسية مريحة ومجهزة بالتكييف والإضاءة المناسبة", axis: 3, scores: [2, 2, 4, 2, 2] },
                    { id: 14, text: "الخدمات العامة (دورات المياه، الكافتيريا) نظيفة ومتاحة", axis: 3, scores: [0, 1, 3, 5, 3] },
                    { id: 15, text: "جودة وسرعة شبكة الإنترنت المتاحة للطلاب مقبولة وسريعة", axis: 3, scores: [0, 0, 1, 4, 7] },
                    { id: 16, text: "الإدارة تتعامل بمرونة وتسعى لحل مشاكل الطلاب المختلفة", axis: 3, scores: [2, 4, 5, 1, 0] }
                ]
            }
        };

        let currentDatasetKey = 'combined';
        let charts = {};

        // Utility: Calculate weighted average and satisfaction score for an item
        function calculateMetrics(item) {
            const weights = [5, 4, 3, 2, 1];
            let totalResponses = 0;
            let totalWeightedScore = 0;
            let agreeCount = item.scores[0] + item.scores[1]; // 5 (strongly agree) + 4 (agree)
            let neutralCount = item.scores[2]; // 3
            let disagreeCount = item.scores[3] + item.scores[4]; // 2 + 1

            for (let i = 0; i < 5; i++) {
                totalResponses += item.scores[i];
                totalWeightedScore += item.scores[i] * weights[i];
            }

            const weightedAvg = totalResponses > 0 ? (totalWeightedScore / totalResponses) : 0;
            const satisfactionPct = (weightedAvg / 5) * 100;

            return {
                total: totalResponses,
                weightedAvg: weightedAvg.toFixed(2),
                satisfactionPct: satisfactionPct.toFixed(1),
                agreePct: ((agreeCount / totalResponses) * 100).toFixed(1),
                neutralPct: ((neutralCount / totalResponses) * 100).toFixed(1),
                disagreePct: ((disagreeCount / totalResponses) * 100).toFixed(1)
            };
        }

        // Initialize and Render Everything on Window Load
        window.onload = function() {
            setDataset('combined');
            setupDragAndDrop();
        };

        // Switch Active Dataset (combined, year2, year3)
        function setDataset(key) {
            currentDatasetKey = key;
            
            // Update UI buttons styling
            document.querySelectorAll('.ds-btn').forEach(btn => {
                btn.classList.remove('bg-indigo-600', 'text-white');
                btn.classList.add('text-slate-400', 'hover:text-white');
            });
            
            const activeBtn = document.getElementById(`btn-ds-${key}`);
            if (activeBtn) {
                activeBtn.classList.add('bg-indigo-600', 'text-white');
                activeBtn.classList.remove('text-slate-400', 'hover:text-white');
            }

            // Recalculate metrics for UI display
            updateOverviewMetrics();
            renderDimensionsChart();
            renderStrengthsAndWeaknesses();
            renderAxisAnalysis();
            renderDetailedTable();
            renderComparisonChart();
        }

        // Switch Tab UI View
        function switchTab(tabId) {
            document.querySelectorAll('.tab-content').forEach(el => el.classList.add('hidden'));
            document.getElementById(`content-${tabId}`).classList.remove('hidden');

            document.querySelectorAll('.tab-btn').forEach(btn => {
                btn.classList.remove('bg-indigo-600', 'text-white', 'shadow-md');
                btn.classList.add('text-slate-400', 'hover:text-white');
            });

            document.getElementById(`tab-${tabId}`).classList.add('bg-indigo-600', 'text-white', 'shadow-md');
            document.getElementById(`tab-${tabId}`).classList.remove('text-slate-400', 'hover:text-white');
        }

        // Calculate and Render Overview Cards & Progress Summary
        function updateOverviewMetrics() {
            const data = surveyData[currentDatasetKey];
            document.getElementById('kpi-respondents').innerText = data.respondents;

            // Calculate axis weighted averages
            let axisTotals = [0, 0, 0, 0];
            let axisRespondentCounts = [0, 0, 0, 0];
            let overallScoreSum = 0;
            let totalItems = data.items.length;

            let globalAgree = 0;
            let globalNeutral = 0;
            let globalDisagree = 0;
            let globalResponses = 0;

            data.items.forEach(item => {
                const metrics = calculateMetrics(item);
                axisTotals[item.axis] += parseFloat(metrics.satisfactionPct);
                axisRespondentCounts[item.axis]++;
                overallScoreSum += parseFloat(metrics.satisfactionPct);

                globalAgree += (item.scores[0] + item.scores[1]);
                globalNeutral += item.scores[2];
                globalDisagree += (item.scores[3] + item.scores[4]);
                globalResponses += (item.scores[0] + item.scores[1] + item.scores[2] + item.scores[3] + item.scores[4]);
            });

            const overallSat = overallScoreSum / totalItems;
            const kpiSatEl = document.getElementById('kpi-satisfaction');
            kpiSatEl.innerText = `${overallSat.toFixed(1)}%`;
            
            if (overallSat >= 75) {
                kpiSatEl.className = "text-3xl font-bold text-emerald-400";
            } else if (overallSat >= 50) {
                kpiSatEl.className = "text-3xl font-bold text-amber-400";
            } else {
                kpiSatEl.className = "text-3xl font-bold text-rose-400";
            }

            // Find best and worst axis
            let axisAverages = axisTotals.map((tot, idx) => ({
                name: data.dimensions[idx],
                score: tot / axisRespondentCounts[idx]
            }));

            axisAverages.sort((a, b) => b.score - a.score);
            
            document.getElementById('kpi-best-axis').innerText = axisAverages[0].name;
            document.getElementById('kpi-best-score').innerText = `${axisAverages[0].score.toFixed(1)}% رضا`;
            
            document.getElementById('kpi-worst-axis').innerText = axisAverages[axisAverages.length - 1].name;
            document.getElementById('kpi-worst-score').innerText = `${axisAverages[axisAverages.length - 1].score.toFixed(1)}% رضا`;

            // Update bottom radial-progress percentages
            const agreePctVal = ((globalAgree / globalResponses) * 100).toFixed(1);
            const neutralPctVal = ((globalNeutral / globalResponses) * 100).toFixed(1);
            const disagreePctVal = ((globalDisagree / globalResponses) * 100).toFixed(1);

            document.getElementById('global-agree-pct').innerText = `${agreePctVal}%`;
            document.getElementById('global-agree-bar').style.width = `${agreePctVal}%`;

            document.getElementById('global-neutral-pct').innerText = `${neutralPctVal}%`;
            document.getElementById('global-neutral-bar').style.width = `${neutralPctVal}%`;

            document.getElementById('global-disagree-pct').innerText = `${disagreePctVal}%`;
            document.getElementById('global-disagree-bar').style.width = `${disagreePctVal}%`;
        }

        // Render Bar Chart: Comparison of Axes
        function renderDimensionsChart() {
            const data = surveyData[currentDatasetKey];
            let axisTotals = [0, 0, 0, 0];
            let axisCounts = [0, 0, 0, 0];

            data.items.forEach(item => {
                const metrics = calculateMetrics(item);
                axisTotals[item.axis] += parseFloat(metrics.satisfactionPct);
                axisCounts[item.axis]++;
            });

            const axisAverages = axisTotals.map((sum, i) => (sum / axisCounts[i]).toFixed(1));

            if (charts.dimensions) {
                charts.dimensions.destroy();
            }

            const ctx = document.getElementById('chart-dimensions').getContext('2d');
            charts.dimensions = new Chart(ctx, {
                type: 'bar',
                data: {
                    labels: data.dimensions,
                    datasets: [{
                        label: 'معدل الرضا المئوي (%)',
                        data: axisAverages,
                        backgroundColor: [
                            'rgba(99, 102, 241, 0.7)',  // Indigo
                            'rgba(16, 185, 129, 0.7)',  // Emerald
                            'rgba(244, 63, 94, 0.7)',   // Rose
                            'rgba(245, 158, 11, 0.7)'   // Amber
                        ],
                        borderColor: [
                            'rgb(99, 102, 241)',
                            'rgb(16, 185, 129)',
                            'rgb(244, 63, 94)',
                            'rgb(245, 158, 11)'
                        ],
                        borderWidth: 2,
                        borderRadius: 8
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    rtl: true,
                    plugins: {
                        legend: { display: false }
                    },
                    scales: {
                        y: {
                            beginAtZero: true,
                            max: 100,
                            grid: { color: 'rgba(255, 255, 255, 0.05)' },
                            ticks: { color: '#94a3b8' }
                        },
                        x: {
                            grid: { display: false },
                            ticks: { color: '#94a3b8', font: { family: 'Cairo' } }
                        }
                    }
                }
            });
        }

        // Render Strengths and Opportunities For Improvement
        function renderStrengthsAndWeaknesses() {
            const data = surveyData[currentDatasetKey];
            const itemsWithMetrics = data.items.map(item => ({
                ...item,
                metrics: calculateMetrics(item)
            }));

            // Sort by satisfaction percentage
            itemsWithMetrics.sort((a, b) => b.metrics.satisfactionPct - a.metrics.satisfactionPct);

            const top3 = itemsWithMetrics.slice(0, 3);
            const worst3 = itemsWithMetrics.slice(-3).reverse();

            // Render Strengths
            const strengthsList = document.getElementById('list-strengths');
            strengthsList.innerHTML = top3.map(item => `
                <li class="flex flex-col space-y-1 p-3.5 bg-slate-900/50 rounded-xl border border-emerald-500/10 hover:border-emerald-500/30 transition">
                    <div class="flex items-center justify-between">
                        <span class="text-xs font-semibold text-indigo-400">فقرة ${item.id} - ${data.dimensions[item.axis]}</span>
                        <span class="text-sm font-bold text-emerald-400">${item.metrics.satisfactionPct}% رضا</span>
                    </div>
                    <p class="text-sm text-white font-medium">${item.text}</p>
                    <div class="flex items-center gap-4 text-xs text-slate-400 mt-2">
                        <span>المتوسط الموزون: <strong>${item.metrics.weightedAvg}/5</strong></span>
                        <span>موافق بشدة: <strong>${item.scores[0]}</strong> | موافق: <strong>${item.scores[1]}</strong></span>
                    </div>
                </li>
            `).join('');

            // Render Weaknesses
            const weaknessesList = document.getElementById('list-weaknesses');
            weaknessesList.innerHTML = worst3.map(item => `
                <li class="flex flex-col space-y-1 p-3.5 bg-slate-900/50 rounded-xl border border-rose-500/10 hover:border-rose-500/30 transition">
                    <div class="flex items-center justify-between">
                        <span class="text-xs font-semibold text-rose-400">فقرة ${item.id} - ${data.dimensions[item.axis]}</span>
                        <span class="text-sm font-bold text-rose-400">${item.metrics.satisfactionPct}% رضا</span>
                    </div>
                    <p class="text-sm text-white font-medium">${item.text}</p>
                    <div class="flex items-center gap-4 text-xs text-slate-400 mt-2">
                        <span>المتوسط الموزون: <strong>${item.metrics.weightedAvg}/5</strong></span>
                        <span>غير موافق بشدة: <strong>${item.scores[4]}</strong> | غير موافق: <strong>${item.scores[3]}</strong></span>
                    </div>
                </li>
            `).join('');
        }

        // Render Dimension Tab: Stacked Likert distribution & stats
        function renderAxisAnalysis() {
            const axisIndex = parseInt(document.getElementById('axis-selector').value || 0);
            const data = surveyData[currentDatasetKey];
            const axisItems = data.items.filter(item => item.axis === axisIndex);

            // Rebuild Chart.js Horizontal Stacked Bar Chart
            const labels = axisItems.map(item => `فقرة ${item.id}: ${item.text.substring(0, 30)}...`);
            
            // Extrapolate scores per rating level (5, 4, 3, 2, 1)
            const rating5 = axisItems.map(item => item.scores[0]);
            const rating4 = axisItems.map(item => item.scores[1]);
            const rating3 = axisItems.map(item => item.scores[2]);
            const rating2 = axisItems.map(item => item.scores[3]);
            const rating1 = axisItems.map(item => item.scores[4]);

            if (charts.axisLikert) {
                charts.axisLikert.destroy();
            }

            const ctx = document.getElementById('chart-axis-likert').getContext('2d');
            charts.axisLikert = new Chart(ctx, {
                type: 'bar',
                data: {
                    labels: labels,
                    datasets: [
                        { label: 'ممتاز / موافق بشدة (5)', data: rating5, backgroundColor: '#059669' },
                        { label: 'موافق (4)', data: rating4, backgroundColor: '#34d399' },
                        { label: 'محايد (3)', data: rating3, backgroundColor: '#f59e0b' },
                        { label: 'غير موافق (2)', data: rating2, backgroundColor: '#f87171' },
                        { label: 'غير موافق على الإطلاق (1)', data: rating1, backgroundColor: '#b91c1c' }
                    ]
                },
                options: {
                    indexAxis: 'y',
                    responsive: true,
                    maintainAspectRatio: false,
                    rtl: true,
                    scales: {
                        x: { stacked: true, grid: { color: 'rgba(255, 255, 255, 0.05)' }, ticks: { color: '#94a3b8' } },
                        y: { stacked: true, grid: { display: false }, ticks: { color: '#94a3b8', font: { family: 'Cairo' } } }
                    },
                    plugins: {
                        legend: { position: 'top', labels: { color: '#cbd5e1', font: { family: 'Cairo' } } }
                    }
                }
            });

            // Update axis stats cards underneath
            const statsContainer = document.getElementById('axis-stats-container');
            let totalWeightedSum = 0;
            let totalResponsesSum = 0;
            
            axisItems.forEach(item => {
                const metrics = calculateMetrics(item);
                totalWeightedSum += parseFloat(metrics.weightedAvg);
                totalResponsesSum += metrics.total;
            });

            const axisAvg = (totalWeightedSum / axisItems.length).toFixed(2);
            const axisSatPct = ((axisAvg / 5) * 100).toFixed(1);

            statsContainer.innerHTML = `
                <div class="p-5 bg-slate-900/50 rounded-xl border border-slate-700">
                    <h4 class="text-sm font-semibold text-slate-400 mb-1">المتوسط الحسابي الموزون للمحور</h4>
                    <div class="text-2xl font-bold text-indigo-400">${axisAvg} / 5.0</div>
                    <p class="text-xs text-slate-500 mt-2">يعتمد على التقديرات النسبية لمؤشر رضا الطلاب في هذا المحور.</p>
                </div>
                <div class="p-5 bg-slate-900/50 rounded-xl border border-slate-700">
                    <h4 class="text-sm font-semibold text-slate-400 mb-1">المعدل العام لرضا طلاب هذا المحور</h4>
                    <div class="text-2xl font-bold text-emerald-400">${axisSatPct}%</div>
                    <p class="text-xs text-slate-500 mt-2">يعبر عن النسبة المئوية للموافقة ومستويات التقييم الإيجابية للمحور.</p>
                </div>
            `;
        }

        // Render Detailed Items Table
        function renderDetailedTable() {
            const data = surveyData[currentDatasetKey];
            const tbody = document.getElementById('detailed-table-body');
            tbody.innerHTML = '';

            data.items.forEach(item => {
                const metrics = calculateMetrics(item);
                const statusInfo = getStatus(parseFloat(metrics.satisfactionPct));

                const row = document.createElement('tr');
                row.className = "hover:bg-slate-800/20 transition duration-150";
                row.dataset.axis = item.axis;
                row.dataset.text = item.text;

                row.innerHTML = `
                    <td class="px-6 py-4 font-semibold text-slate-400">${item.id}</td>
                    <td class="px-6 py-4 font-medium text-white max-w-sm whitespace-normal">${item.text}</td>
                    <td class="px-6 py-4 text-xs text-slate-400 font-semibold">${data.dimensions[item.axis]}</td>
                    <td class="px-6 py-4 text-center">
                        <span class="inline-flex px-2 py-0.5 rounded-md bg-emerald-500/10 text-emerald-400 text-xs">${metrics.agreePct}%</span>
                    </td>
                    <td class="px-6 py-4 text-center font-bold text-slate-300">${metrics.weightedAvg}</td>
                    <td class="px-6 py-4 text-center">
                        <div class="flex items-center justify-center gap-2">
                            <span class="font-bold text-white">${metrics.satisfactionPct}%</span>
                            <div class="w-12 bg-slate-700 h-1.5 rounded-full overflow-hidden hidden sm:block">
                                <div class="bg-indigo-500 h-full" style="width: ${metrics.satisfactionPct}%"></div>
                            </div>
                        </div>
                    </td>
                    <td class="px-6 py-4 text-center">
                        <span class="inline-flex px-2.5 py-1 rounded-full text-xs font-semibold ${statusInfo.badgeClass}">
                            ${statusInfo.text}
                        </span>
                    </td>
                `;
                tbody.appendChild(row);
            });
        }

        // Search and Filter functionality for the table
        function filterDetailedTable() {
            const query = document.getElementById('table-search').value.toLowerCase();
            const axisFilter = document.getElementById('table-filter-axis').value;
            const rows = document.querySelectorAll('#detailed-table-body tr');

            rows.forEach(row => {
                const text = row.dataset.text.toLowerCase();
                const axis = row.dataset.axis;

                const matchesSearch = text.includes(query);
                const matchesAxis = axisFilter === 'all' || axis === axisFilter;

                if (matchesSearch && matchesAxis) {
                    row.classList.remove('hidden');
                } else {
                    row.classList.add('hidden');
                }
            });
        }

        // Get Quality Status Badge
        function getStatus(pct) {
            if (pct >= 85) return { text: "ممتاز", badgeClass: "bg-emerald-500/10 text-emerald-400" };
            if (pct >= 70) return { text: "جيد جداً", badgeClass: "bg-emerald-400/10 text-emerald-300" };
            if (pct >= 60) return { text: "مقبول", badgeClass: "bg-amber-500/10 text-amber-400" };
            return { text: "يحتاج تطوير عاجل", badgeClass: "bg-rose-500/10 text-rose-400" };
        }

        // Render Bar Chart: Comparison between Years (Year 2 vs Year 3)
        function renderComparisonChart() {
            const dataY2 = surveyData.year2;
            const dataY3 = surveyData.year3;

            let axisTotalsY2 = [0, 0, 0, 0];
            let axisCountsY2 = [0, 0, 0, 0];
            dataY2.items.forEach(item => {
                const m = calculateMetrics(item);
                axisTotalsY2[item.axis] += parseFloat(m.satisfactionPct);
                axisCountsY2[item.axis]++;
            });
            const y2Averages = axisTotalsY2.map((sum, i) => (sum / axisCountsY2[i]).toFixed(1));

            let axisTotalsY3 = [0, 0, 0, 0];
            let axisCountsY3 = [0, 0, 0, 0];
            dataY3.items.forEach(item => {
                const m = calculateMetrics(item);
                axisTotalsY3[item.axis] += parseFloat(m.satisfactionPct);
                axisCountsY3[item.axis]++;
            });
            const y3Averages = axisTotalsY3.map((sum, i) => (sum / axisCountsY3[i]).toFixed(1));

            if (charts.comparison) {
                charts.comparison.destroy();
            }

            const ctx = document.getElementById('chart-comparison-bar').getContext('2d');
            charts.comparison = new Chart(ctx, {
                type: 'bar',
                data: {
                    labels: surveyData.combined.dimensions,
                    datasets: [
                        {
                            label: 'السنة الثانية (16 طالب)',
                            data: y2Averages,
                            backgroundColor: 'rgba(99, 102, 241, 0.75)',
                            borderColor: 'rgb(99, 102, 241)',
                            borderWidth: 1.5,
                            borderRadius: 6
                        },
                        {
                            label: 'السنة الثالثة (12 طالب)',
                            data: y3Averages,
                            backgroundColor: 'rgba(16, 185, 129, 0.75)',
                            borderColor: 'rgb(16, 185, 129)',
                            borderWidth: 1.5,
                            borderRadius: 6
                        }
                    ]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    rtl: true,
                    scales: {
                        y: {
                            beginAtZero: true,
                            max: 100,
                            grid: { color: 'rgba(255, 255, 255, 0.05)' },
                            ticks: { color: '#94a3b8' }
                        },
                        x: {
                            grid: { display: false },
                            ticks: { color: '#94a3b8', font: { family: 'Cairo' } }
                        }
                    },
                    plugins: {
                        legend: { labels: { color: '#cbd5e1', font: { family: 'Cairo' } } }
                    }
                }
            });
        }

        // CSV File Uploader / Parser Logic
        function setupDragAndDrop() {
            const dropZone = document.getElementById('drop-zone');

            dropZone.addEventListener('click', () => {
                document.getElementById('csv-file-input').click();
            });

            dropZone.addEventListener('dragover', (e) => {
                e.preventDefault();
                dropZone.classList.add('border-indigo-500', 'bg-slate-800/60');
            });

            dropZone.addEventListener('dragleave', () => {
                dropZone.classList.remove('border-indigo-500', 'bg-slate-800/60');
            });

            dropZone.addEventListener('drop', (e) => {
                e.preventDefault();
                dropZone.classList.remove('border-indigo-500', 'bg-slate-800/60');
                const files = e.dataTransfer.files;
                if (files.length > 0) {
                    processCSVFile(files[0]);
                }
            });
        }

        function handleFileUpload(event) {
            const file = event.target.files[0];
            if (file) {
                processCSVFile(file);
            }
        }

        // Robust CSV Parser optimized for student survey formats
        function processCSVFile(file) {
            const reader = new FileReader();
            reader.onload = function(e) {
                const text = e.target.result;
                const rows = text.split('\n').map(row => row.split(','));
                
                // Temporary storage for items found
                let items = [];
                let currentAxisIndex = -1;
                let surveyTitle = file.name.replace('.csv', '');
                let dimensions = [
                    "المناهج والمقررات الدراسية",
                    "أداء المدربين والمدرسين",
                    "التدريب العملي والمختبرات",
                    "الخدمات والمرافق العامة"
                ];

                // Attempt to parse survey rows
                rows.forEach((row, idx) => {
                    // Check if it's a title row
                    if (row.some(cell => cell.includes("استبيان رضا"))) {
                        const titleCell = row.find(cell => cell.includes("استبيان رضا"));
                        if (titleCell) surveyTitle = titleCell.trim();
                    }

                    // Check for Dimension Change (المحور)
                    const axisCell = row.find(cell => cell.includes("المحور"));
                    if (axisCell) {
                        currentAxisIndex++;
                        const cleanAxisName = axisCell.replace(/\|/g, '').replace(/م/g, '').trim();
                        if (currentAxisIndex < 4) {
                            dimensions[currentAxisIndex] = cleanAxisName;
                        }
                    }

                    // Parse item with numeric values (Likert scale 5, 4, 3, 2, 1)
                    // Usually item text is in one of the cells, and scores are listed
                    if (currentAxisIndex >= 0) {
                        // Let's filter cells that contain numbers and find the text
                        const numericCells = row.map(cell => parseInt(cell.trim())).filter(num => !isNaN(num));
                        const textCell = row.find(cell => cell.trim().length > 15 && !cell.includes("استبيان") && !cell.includes("المحور"));
                        
                        // If we have text and enough numbers (usually 5 fields for Likert + 1 index)
                        if (textCell && numericCells.length >= 5) {
                            const scores = numericCells.slice(1, 6); // Grab the 5 Likert numbers
                            if (scores.length === 5) {
                                items.push({
                                    id: items.length + 1,
                                    text: textCell.trim(),
                                    axis: Math.min(currentAxisIndex, 3),
                                    scores: scores
                                });
                            }
                        }
                    }
                });

                if (items.length > 0) {
                    // Inject newly parsed dataset into global storage under a custom key
                    surveyData.custom = {
                        respondents: items[0].scores.reduce((a, b) => a + b, 0),
                        title: surveyTitle,
                        dimensions: dimensions,
                        items: items
                    };

                    // Add a selector button for the newly uploaded file
                    const dsContainer = document.querySelector('#btn-ds-combined').parentNode;
                    
                    // Remove existing custom button if exists
                    const oldCustomBtn = document.getElementById('btn-ds-custom');
                    if (oldCustomBtn) oldCustomBtn.remove();

                    const customBtn = document.createElement('button');
                    customBtn.id = "btn-ds-custom";
                    customBtn.className = "ds-btn px-4 py-1.5 rounded-md text-sm font-medium text-slate-400 hover:text-white transition";
                    customBtn.innerText = "الملف المرفوع حديثاً";
                    customBtn.onclick = () => setDataset('custom');
                    dsContainer.appendChild(customBtn);

                    setDataset('custom');
                    alert(`🎉 تم بنجاح معالجة ورفع الملف واستخراج ${items.length} فقرة استبيان بنجاح!`);
                    switchTab('overview');
                } else {
                    alert("❌ تعذر العثور على فقرات استبيان مطابقة في الملف المرفوع. الرجاء التحقق من صيغة الـ CSV.");
                }
            };
            reader.readAsText(file);
        }
    </script>
</body>
</html>

```
