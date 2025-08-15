<!DOCTYPE html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Impact of IT Consulting | Jad Wa Dee IT Consulting</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #F4F6F7;
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 500px;
            margin-left: auto;
            margin-right: auto;
            height: 300px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 350px;
            }
        }
        .kpi-card {
            background: linear-gradient(135deg, #FFC700, #FF8F00);
        }
    </style>
</head>
<body class="text-[#34495E]">

    <div class="container mx-auto p-4 md:p-8 max-w-7xl">
        <div class="flex justify-end mb-4">
            <button id="lang-th" class="px-4 py-2 mr-2 rounded-lg font-bold bg-[#FF8F00] text-white">TH</button>
            <button id="lang-en" class="px-4 py-2 rounded-lg font-bold bg-[#2ECC71] text-white">EN</button>
        </div>

        <div id="en-content">
            <header class="text-center mb-12">
                <h1 class="text-4xl md:text-5xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-[#FF8F00] to-[#2ECC71] mb-2">Jad Wa Dee IT Consulting</h1>
                <p class="text-xl md:text-2xl font-semibold">Transforming Your Business Through Technology</p>
                <p class="mt-2 text-gray-600 max-w-3xl mx-auto">In today's fast-paced digital world, inefficient IT can be a major roadblock to growth. Discover how strategic IT consulting can streamline operations, boost productivity, and drive success.</p>
            </header>

            <main class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <section class="md:col-span-2 bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-4">The Hidden Costs of Outdated IT</h2>
                    <p class="text-center text-gray-600 mb-8 max-w-4xl mx-auto">Many businesses underestimate how much time and money is lost to inefficient systems. These small daily frustrations add up to significant annual losses, hindering potential and frustrating employees.</p>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
                        <div>
                            <h3 class="text-xl font-semibold text-center mb-2">Where Does the Time Go?</h3>
                            <div class="chart-container h-64 md:h-80">
                                <canvas id="timeWastedChart-en"></canvas>
                            </div>
                        </div>
                        <div class="text-center">
                            <div class="kpi-card text-white p-8 rounded-xl shadow-lg">
                                <p class="text-lg font-semibold">Average Hours Lost Annually</p>
                                <p class="text-6xl font-bold my-2">250</p>
                                <p class="text-lg">per employee</p>
                            </div>
                            <p class="mt-4 text-gray-600">This translates to over six weeks of lost productivity per employee every year, directly impacting your bottom line and innovation capacity.</p>
                        </div>
                    </div>
                </section>

                <section class="md:col-span-2 bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-6">Our Proven Path to Modernization</h2>
                    <p class="text-center text-gray-600 mb-8 max-w-4xl mx-auto">We follow a structured, four-step process to ensure a smooth and successful digital transformation. Our goal is to understand your unique challenges and implement tailored solutions that deliver measurable results.</p>
                    <div class="flex flex-col md:flex-row justify-around items-center space-y-6 md:space-y-0 md:space-x-4">
                        <div class="flex items-center flex-col text-center w-52">
                            <div class="bg-[#FFC700] text-white rounded-full w-20 h-20 flex items-center justify-center text-3xl font-bold shadow-md">1</div>
                            <h3 class="text-lg font-semibold mt-3">Assess</h3>
                            <p class="text-sm text-gray-500">We dive deep into your current systems to identify pain points and opportunities.</p>
                        </div>
                        <div class="text-3xl text-gray-300 hidden md:block">&rarr;</div>
                        <div class="flex items-center flex-col text-center w-52">
                            <div class="bg-[#FF8F00] text-white rounded-full w-20 h-20 flex items-center justify-center text-3xl font-bold shadow-md">2</div>
                            <h3 class="text-lg font-semibold mt-3">Strategize</h3>
                            <p class="text-sm text-gray-500">We develop a custom roadmap with clear goals, timelines, and budgets.</p>
                        </div>
                        <div class="text-3xl text-gray-300 hidden md:block">&rarr;</div>
                        <div class="flex items-center flex-col text-center w-52">
                            <div class="bg-[#2ECC71] text-white rounded-full w-20 h-20 flex items-center justify-center text-3xl font-bold shadow-md">3</div>
                            <h3 class="text-lg font-semibold mt-3">Implement</h3>
                            <p class="text-sm text-gray-500">Our experts deploy new solutions with minimal disruption to your business.</p>
                        </div>
                         <div class="text-3xl text-gray-300 hidden md:block">&rarr;</div>
                        <div class="flex items-center flex-col text-center w-52">
                            <div class="bg-[#34495E] text-white rounded-full w-20 h-20 flex items-center justify-center text-3xl font-bold shadow-md">4</div>
                            <h3 class="text-lg font-semibold mt-3">Support</h3>
                            <p class="text-sm text-gray-500">We provide ongoing support to ensure your systems run smoothly.</p>
                        </div>
                    </div>
                </section>

                <section class="bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-2">The "Jad Wa Dee" Impact</h2>
                    <p class="text-center text-gray-600 mb-6">Our solutions deliver tangible improvements across key business metrics. By optimizing your IT infrastructure, we help you reduce costs, empower your team, and secure your valuable data.</p>
                    <div class="chart-container h-80 md:h-96">
                        <canvas id="impactChart-en"></canvas>
                    </div>
                </section>

                <section class="bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-2">Driving Sustainable Growth</h2>
                     <p class="text-center text-gray-600 mb-6">A modernized IT environment isn't just about efficiency; it's a catalyst for growth. Our clients consistently see a significant increase in revenue after our strategic interventions.</p>
                    <div class="chart-container h-80 md:h-96">
                        <canvas id="growthChart-en"></canvas>
                    </div>
                </section>

                <section class="md:col-span-2 bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-4">Excellence in Every Area</h2>
                    <p class="text-center text-gray-600 mb-8 max-w-4xl mx-auto">We pride ourselves on delivering a comprehensive, high-quality service. Our client satisfaction scores reflect our commitment to expertise, communication, and delivering a positive return on investment.</p>
                    <div class="chart-container h-80 md:h-96 max-w-md">
                        <canvas id="satisfactionChart-en"></canvas>
                    </div>
                </section>
            </main>
        </div>

        <div id="th-content" class="hidden">
            <header class="text-center mb-12">
                <h1 class="text-4xl md:text-5xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-[#FF8F00] to-[#2ECC71] mb-2">จัด ว่า ดี ไอที คอนเซาท์ติ้ง</h1>
                <p class="text-xl md:text-2xl font-semibold">พลิกโฉมธุรกิจของคุณด้วยเทคโนโลยี</p>
                <p class="mt-2 text-gray-600 max-w-3xl mx-auto">ในยุคดิจิทัลที่เปลี่ยนแปลงอย่างรวดเร็ว ระบบไอทีที่ไม่มีประสิทธิภาพอาจเป็นอุปสรรคสำคัญต่อการเติบโต มาค้นพบว่าการให้คำปรึกษาด้านไอทีเชิงกลยุทธ์จะช่วยปรับปรุงการดำเนินงาน เพิ่มประสิทธิภาพ และขับเคลื่อนความสำเร็จได้อย่างไร</p>
            </header>

            <main class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <section class="md:col-span-2 bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-4">ต้นทุนที่มองไม่เห็นของระบบไอทีที่ล้าสมัย</h2>
                    <p class="text-center text-gray-600 mb-8 max-w-4xl mx-auto">ธุรกิจจำนวนมากประเมินค่าใช้จ่ายที่มองไม่เห็นจากการทำงานของระบบที่ไม่มีประสิทธิภาพต่ำเกินไป ปัญหาเล็กๆ น้อยๆ ที่เกิดขึ้นทุกวันเหล่านี้สะสมจนกลายเป็นความสูญเสียครั้งใหญ่ในแต่ละปี</p>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
                        <div>
                            <h3 class="text-xl font-semibold text-center mb-2">เวลาที่สูญเสียไปอยู่ที่ไหน?</h3>
                            <div class="chart-container h-64 md:h-80">
                                <canvas id="timeWastedChart-th"></canvas>
                            </div>
                        </div>
                        <div class="text-center">
                            <div class="kpi-card text-white p-8 rounded-xl shadow-lg">
                                <p class="text-lg font-semibold">เวลาเฉลี่ยที่สูญเสียต่อปี</p>
                                <p class="text-6xl font-bold my-2">250</p>
                                <p class="text-lg">ต่อพนักงาน</p>
                            </div>
                            <p class="mt-4 text-gray-600">ซึ่งเทียบเท่ากับการสูญเสียประสิทธิภาพการทำงานกว่า 6 สัปดาห์ต่อพนักงานหนึ่งคนในแต่ละปี ส่งผลกระทบโดยตรงต่อผลกำไรและความสามารถในการสร้างสรรค์นวัตกรรมของคุณ</p>
                        </div>
                    </div>
                </section>

                <section class="md:col-span-2 bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-6">เส้นทางสู่ความทันสมัยที่เราพิสูจน์แล้ว</h2>
                    <p class="text-center text-gray-600 mb-8 max-w-4xl mx-auto">เราใช้กระบวนการ 4 ขั้นตอนที่มีโครงสร้างชัดเจน เพื่อให้การเปลี่ยนแปลงทางดิจิทัลเป็นไปอย่างราบรื่นและประสบความสำเร็จ เป้าหมายของเราคือการทำความเข้าใจความท้าทายเฉพาะของธุรกิจคุณ และนำโซลูชันที่ปรับแต่งมาโดยเฉพาะไปใช้</p>
                    <div class="flex flex-col md:flex-row justify-around items-center space-y-6 md:space-y-0 md:space-x-4">
                        <div class="flex items-center flex-col text-center w-52">
                            <div class="bg-[#FFC700] text-white rounded-full w-20 h-20 flex items-center justify-center text-3xl font-bold shadow-md">1</div>
                            <h3 class="text-lg font-semibold mt-3">ประเมิน</h3>
                            <p class="text-sm text-gray-500">เราจะเจาะลึกเข้าไปในระบบปัจจุบันของคุณเพื่อระบุจุดที่ต้องแก้ไขและโอกาสในการพัฒนา</p>
                        </div>
                        <div class="text-3xl text-gray-300 hidden md:block">&rarr;</div>
                        <div class="flex items-center flex-col text-center w-52">
                            <div class="bg-[#FF8F00] text-white rounded-full w-20 h-20 flex items-center justify-center text-3xl font-bold shadow-md">2</div>
                            <h3 class="text-lg font-semibold mt-3">วางแผน</h3>
                            <p class="text-sm text-gray-500">เราจะพัฒนากลยุทธ์เฉพาะบุคคลพร้อมเป้าหมายที่ชัดเจน กำหนดเวลาและงบประมาณ</p>
                        </div>
                        <div class="text-3xl text-gray-300 hidden md:block">&rarr;</div>
                        <div class="flex items-center flex-col text-center w-52">
                            <div class="bg-[#2ECC71] text-white rounded-full w-20 h-20 flex items-center justify-center text-3xl font-bold shadow-md">3</div>
                            <h3 class="text-lg font-semibold mt-3">นำไปใช้</h3>
                            <p class="text-sm text-gray-500">ผู้เชี่ยวชาญของเราจะนำโซลูชันใหม่ๆ ไปใช้โดยสร้างความติดขัดให้น้อยที่สุดต่อธุรกิจของคุณ</p>
                        </div>
                         <div class="text-3xl text-gray-300 hidden md:block">&rarr;</div>
                        <div class="flex items-center flex-col text-center w-52">
                            <div class="bg-[#34495E] text-white rounded-full w-20 h-20 flex items-center justify-center text-3xl font-bold shadow-md">4</div>
                            <h3 class="text-lg font-semibold mt-3">สนับสนุน</h3>
                            <p class="text-sm text-gray-500">เราให้การสนับสนุนอย่างต่อเนื่องเพื่อให้ระบบของคุณทำงานได้อย่างราบรื่น</p>
                        </div>
                    </div>
                </section>

                <section class="bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-2">ผลกระทบจาก "จัด ว่า ดี"</h2>
                    <p class="text-center text-gray-600 mb-6">โซลูชันของเราช่วยสร้างการพัฒนาที่จับต้องได้ในตัวชี้วัดทางธุรกิจที่สำคัญ ด้วยการเพิ่มประสิทธิภาพโครงสร้างพื้นฐานด้านไอที เราช่วยคุณลดต้นทุน เพิ่มศักยภาพให้กับทีม และปกป้องข้อมูลอันมีค่าของคุณ</p>
                    <div class="chart-container h-80 md:h-96">
                        <canvas id="impactChart-th"></canvas>
                    </div>
                </section>

                <section class="bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-2">การขับเคลื่อนการเติบโตอย่างยั่งยืน</h2>
                     <p class="text-center text-gray-600 mb-6">สภาพแวดล้อมไอทีที่ทันสมัยไม่ได้เป็นเพียงเรื่องของประสิทธิภาพเท่านั้น แต่ยังเป็นตัวขับเคลื่อนการเติบโตอีกด้วย ลูกค้าของเรามีการเติบโตของรายได้เพิ่มขึ้นอย่างต่อเนื่องหลังจากการใช้กลยุทธ์ของเรา</p>
                    <div class="chart-container h-80 md:h-96">
                        <canvas id="growthChart-th"></canvas>
                    </div>
                </section>

                <section class="md:col-span-2 bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-4">ความเป็นเลิศในทุกด้าน</h2>
                    <p class="text-center text-gray-600 mb-8 max-w-4xl mx-auto">เราภาคภูมิใจที่ได้มอบบริการที่ครอบคลุมและมีคุณภาพสูง ผลสำรวจความพึงพอใจของลูกค้าสะท้อนถึงความมุ่งมั่นของเราในเรื่องความเชี่ยวชาญ การสื่อสาร การตรงต่อเวลา และการมอบผลตอบแทนจากการลงทุน</p>
                    <div class="chart-container h-80 md:h-96 max-w-md">
                        <canvas id="satisfactionChart-th"></canvas>
                    </div>
                </section>
            </main>
        </div>

        <div id="th-content" class="hidden">
            <header class="text-center mb-12">
                <h1 class="text-4xl md:text-5xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-[#FF8F00] to-[#2ECC71] mb-2">จัด ว่า ดี ไอที คอนเซาท์ติ้ง</h1>
                <p class="text-xl md:text-2xl font-semibold">พลิกโฉมธุรกิจของคุณด้วยเทคโนโลยี</p>
                <p class="mt-2 text-gray-600 max-w-3xl mx-auto">ในยุคดิจิทัลที่เปลี่ยนแปลงอย่างรวดเร็ว ระบบไอทีที่ไม่มีประสิทธิภาพอาจเป็นอุปสรรคสำคัญต่อการเติบโต มาค้นพบว่าการให้คำปรึกษาด้านไอทีเชิงกลยุทธ์จะช่วยปรับปรุงการดำเนินงาน เพิ่มประสิทธิภาพ และขับเคลื่อนความสำเร็จได้อย่างไร</p>
            </header>

            <main class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <section class="md:col-span-2 bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-4">ต้นทุนที่มองไม่เห็นของระบบไอทีที่ล้าสมัย</h2>
                    <p class="text-center text-gray-600 mb-8 max-w-4xl mx-auto">ธุรกิจจำนวนมากประเมินค่าใช้จ่ายที่มองไม่เห็นจากการทำงานของระบบที่ไม่มีประสิทธิภาพต่ำเกินไป ปัญหาเล็กๆ น้อยๆ ที่เกิดขึ้นทุกวันเหล่านี้สะสมจนกลายเป็นความสูญเสียครั้งใหญ่ในแต่ละปี</p>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
                        <div>
                            <h3 class="text-xl font-semibold text-center mb-2">เวลาที่สูญเสียไปอยู่ที่ไหน?</h3>
                            <div class="chart-container h-64 md:h-80">
                                <canvas id="timeWastedChart-th"></canvas>
                            </div>
                        </div>
                        <div class="text-center">
                            <div class="kpi-card text-white p-8 rounded-xl shadow-lg">
                                <p class="text-lg font-semibold">เวลาเฉลี่ยที่สูญเสียต่อปี</p>
                                <p class="text-6xl font-bold my-2">250</p>
                                <p class="text-lg">ต่อพนักงาน</p>
                            </div>
                            <p class="mt-4 text-gray-600">ซึ่งเทียบเท่ากับการสูญเสียประสิทธิภาพการทำงานกว่า 6 สัปดาห์ต่อพนักงานหนึ่งคนในแต่ละปี ส่งผลกระทบโดยตรงต่อผลกำไรและความสามารถในการสร้างสรรค์นวัตกรรมของคุณ</p>
                        </div>
                    </div>
                </section>

                <section class="md:col-span-2 bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-6">เส้นทางสู่ความทันสมัยที่เราพิสูจน์แล้ว</h2>
                    <p class="text-center text-gray-600 mb-8 max-w-4xl mx-auto">เราใช้กระบวนการ 4 ขั้นตอนที่มีโครงสร้างชัดเจน เพื่อให้การเปลี่ยนแปลงทางดิจิทัลเป็นไปอย่างราบรื่นและประสบความสำเร็จ เป้าหมายของเราคือการทำความเข้าใจความท้าทายเฉพาะของธุรกิจคุณ และนำโซลูชันที่ปรับแต่งมาโดยเฉพาะไปใช้</p>
                    <div class="flex flex-col md:flex-row justify-around items-center space-y-6 md:space-y-0 md:space-x-4">
                        <div class="flex items-center flex-col text-center w-52">
                            <div class="bg-[#FFC700] text-white rounded-full w-20 h-20 flex items-center justify-center text-3xl font-bold shadow-md">1</div>
                            <h3 class="text-lg font-semibold mt-3">ประเมิน</h3>
                            <p class="text-sm text-gray-500">เราจะเจาะลึกเข้าไปในระบบปัจจุบันของคุณเพื่อระบุจุดที่ต้องแก้ไขและโอกาสในการพัฒนา</p>
                        </div>
                        <div class="text-3xl text-gray-300 hidden md:block">&rarr;</div>
                        <div class="flex items-center flex-col text-center w-52">
                            <div class="bg-[#FF8F00] text-white rounded-full w-20 h-20 flex items-center justify-center text-3xl font-bold shadow-md">2</div>
                            <h3 class="text-lg font-semibold mt-3">วางแผน</h3>
                            <p class="text-sm text-gray-500">เราจะพัฒนากลยุทธ์เฉพาะบุคคลพร้อมเป้าหมายที่ชัดเจน กำหนดเวลาและงบประมาณ</p>
                        </div>
                        <div class="text-3xl text-gray-300 hidden md:block">&rarr;</div>
                        <div class="flex items-center flex-col text-center w-52">
                            <div class="bg-[#2ECC71] text-white rounded-full w-20 h-20 flex items-center justify-center text-3xl font-bold shadow-md">3</div>
                            <h3 class="text-lg font-semibold mt-3">นำไปใช้</h3>
                            <p class="text-sm text-gray-500">ผู้เชี่ยวชาญของเราจะนำโซลูชันใหม่ๆ ไปใช้โดยสร้างความติดขัดให้น้อยที่สุดต่อธุรกิจของคุณ</p>
                        </div>
                         <div class="text-3xl text-gray-300 hidden md:block">&rarr;</div>
                        <div class="flex items-center flex-col text-center w-52">
                            <div class="bg-[#34495E] text-white rounded-full w-20 h-20 flex items-center justify-center text-3xl font-bold shadow-md">4</div>
                            <h3 class="text-lg font-semibold mt-3">สนับสนุน</h3>
                            <p class="text-sm text-gray-500">เราให้การสนับสนุนอย่างต่อเนื่องเพื่อให้ระบบของคุณทำงานได้อย่างราบรื่น</p>
                        </div>
                    </div>
                </section>

                <section class="bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-2">ผลกระทบจาก "จัด ว่า ดี"</h2>
                    <p class="text-center text-gray-600 mb-6">โซลูชันของเราช่วยสร้างการพัฒนาที่จับต้องได้ในตัวชี้วัดทางธุรกิจที่สำคัญ ด้วยการเพิ่มประสิทธิภาพโครงสร้างพื้นฐานด้านไอที เราช่วยคุณลดต้นทุน เพิ่มศักยภาพให้กับทีม และปกป้องข้อมูลอันมีค่าของคุณ</p>
                    <div class="chart-container h-80 md:h-96">
                        <canvas id="impactChart-th"></canvas>
                    </div>
                </section>

                <section class="bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-2">การขับเคลื่อนการเติบโตอย่างยั่งยืน</h2>
                     <p class="text-center text-gray-600 mb-6">สภาพแวดล้อมไอทีที่ทันสมัยไม่ได้เป็นเพียงเรื่องของประสิทธิภาพเท่านั้น แต่ยังเป็นตัวขับเคลื่อนการเติบโตอีกด้วย ลูกค้าของเรามีการเติบโตของรายได้เพิ่มขึ้นอย่างต่อเนื่องหลังจากการใช้กลยุทธ์ของเรา</p>
                    <div class="chart-container h-80 md:h-96">
                        <canvas id="growthChart-th"></canvas>
                    </div>
                </section>

                <section class="md:col-span-2 bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-4">ความเป็นเลิศในทุกด้าน</h2>
                    <p class="text-center text-gray-600 mb-8 max-w-4xl mx-auto">เราภาคภูมิใจที่ได้มอบบริการที่ครอบคลุมและมีคุณภาพสูง ผลสำรวจความพึงพอใจของลูกค้าสะท้อนถึงความมุ่งมั่นของเราในเรื่องความเชี่ยวชาญ การสื่อสาร การตรงต่อเวลา และการมอบผลตอบแทนจากการลงทุน</p>
                    <div class="chart-container h-80 md:h-96 max-w-md">
                        <canvas id="satisfactionChart-th"></canvas>
                    </div>
                </section>
            </main>
        </div>

        <div id="th-content" class="hidden">
            <header class="text-center mb-12">
                <h1 class="text-4xl md:text-5xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-[#FF8F00] to-[#2ECC71] mb-2">จัด ว่า ดี ไอที คอนเซาท์ติ้ง</h1>
                <p class="text-xl md:text-2xl font-semibold">พลิกโฉมธุรกิจของคุณด้วยเทคโนโลยี</p>
                <p class="mt-2 text-gray-600 max-w-3xl mx-auto">ในยุคดิจิทัลที่เปลี่ยนแปลงอย่างรวดเร็ว ระบบไอทีที่ไม่มีประสิทธิภาพอาจเป็นอุปสรรคสำคัญต่อการเติบโต มาค้นพบว่าการให้คำปรึกษาด้านไอทีเชิงกลยุทธ์จะช่วยปรับปรุงการดำเนินงาน เพิ่มประสิทธิภาพ และขับเคลื่อนความสำเร็จได้อย่างไร</p>
            </header>

            <main class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <section class="md:col-span-2 bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-4">ต้นทุนที่มองไม่เห็นของระบบไอทีที่ล้าสมัย</h2>
                    <p class="text-center text-gray-600 mb-8 max-w-4xl mx-auto">ธุรกิจจำนวนมากประเมินค่าใช้จ่ายที่มองไม่เห็นจากการทำงานของระบบที่ไม่มีประสิทธิภาพต่ำเกินไป ปัญหาเล็กๆ น้อยๆ ที่เกิดขึ้นทุกวันเหล่านี้สะสมจนกลายเป็นความสูญเสียครั้งใหญ่ในแต่ละปี</p>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
                        <div>
                            <h3 class="text-xl font-semibold text-center mb-2">เวลาที่สูญเสียไปอยู่ที่ไหน?</h3>
                            <div class="chart-container h-64 md:h-80">
                                <canvas id="timeWastedChart-th"></canvas>
                            </div>
                        </div>
                        <div class="text-center">
                            <div class="kpi-card text-white p-8 rounded-xl shadow-lg">
                                <p class="text-lg font-semibold">เวลาเฉลี่ยที่สูญเสียต่อปี</p>
                                <p class="text-6xl font-bold my-2">250</p>
                                <p class="text-lg">ต่อพนักงาน</p>
                            </div>
                            <p class="mt-4 text-gray-600">ซึ่งเทียบเท่ากับการสูญเสียประสิทธิภาพการทำงานกว่า 6 สัปดาห์ต่อพนักงานหนึ่งคนในแต่ละปี ส่งผลกระทบโดยตรงต่อผลกำไรและความสามารถในการสร้างสรรค์นวัตกรรมของคุณ</p>
                        </div>
                    </div>
                </section>

                <section class="md:col-span-2 bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-6">เส้นทางสู่ความทันสมัยที่เราพิสูจน์แล้ว</h2>
                    <p class="text-center text-gray-600 mb-8 max-w-4xl mx-auto">เราใช้กระบวนการ 4 ขั้นตอนที่มีโครงสร้างชัดเจน เพื่อให้การเปลี่ยนแปลงทางดิจิทัลเป็นไปอย่างราบรื่นและประสบความสำเร็จ เป้าหมายของเราคือการทำความเข้าใจความท้าทายเฉพาะของธุรกิจคุณ และนำโซลูชันที่ปรับแต่งมาโดยเฉพาะไปใช้</p>
                    <div class="flex flex-col md:flex-row justify-around items-center space-y-6 md:space-y-0 md:space-x-4">
                        <div class="flex items-center flex-col text-center w-52">
                            <div class="bg-[#FFC700] text-white rounded-full w-20 h-20 flex items-center justify-center text-3xl font-bold shadow-md">1</div>
                            <h3 class="text-lg font-semibold mt-3">ประเมิน</h3>
                            <p class="text-sm text-gray-500">เราจะเจาะลึกเข้าไปในระบบปัจจุบันของคุณเพื่อระบุจุดที่ต้องแก้ไขและโอกาสในการพัฒนา</p>
                        </div>
                        <div class="text-3xl text-gray-300 hidden md:block">&rarr;</div>
                        <div class="flex items-center flex-col text-center w-52">
                            <div class="bg-[#FF8F00] text-white rounded-full w-20 h-20 flex items-center justify-center text-3xl font-bold shadow-md">2</div>
                            <h3 class="text-lg font-semibold mt-3">วางแผน</h3>
                            <p class="text-sm text-gray-500">เราจะพัฒนากลยุทธ์เฉพาะบุคคลพร้อมเป้าหมายที่ชัดเจน กำหนดเวลาและงบประมาณ</p>
                        </div>
                        <div class="text-3xl text-gray-300 hidden md:block">&rarr;</div>
                        <div class="flex items-center flex-col text-center w-52">
                            <div class="bg-[#2ECC71] text-white rounded-full w-20 h-20 flex items-center justify-center text-3xl font-bold shadow-md">3</div>
                            <h3 class="text-lg font-semibold mt-3">นำไปใช้</h3>
                            <p class="text-sm text-gray-500">ผู้เชี่ยวชาญของเราจะนำโซลูชันใหม่ๆ ไปใช้โดยสร้างความติดขัดให้น้อยที่สุดต่อธุรกิจของคุณ</p>
                        </div>
                         <div class="text-3xl text-gray-300 hidden md:block">&rarr;</div>
                        <div class="flex items-center flex-col text-center w-52">
                            <div class="bg-[#34495E] text-white rounded-full w-20 h-20 flex items-center justify-center text-3xl font-bold shadow-md">4</div>
                            <h3 class="text-lg font-semibold mt-3">สนับสนุน</h3>
                            <p class="text-sm text-gray-500">เราให้การสนับสนุนอย่างต่อเนื่องเพื่อให้ระบบของคุณทำงานได้อย่างราบรื่น</p>
                        </div>
                    </div>
                </section>

                <section class="bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-2">ผลกระทบจาก "จัด ว่า ดี"</h2>
                    <p class="text-center text-gray-600 mb-6">โซลูชันของเราช่วยสร้างการพัฒนาที่จับต้องได้ในตัวชี้วัดทางธุรกิจที่สำคัญ ด้วยการเพิ่มประสิทธิภาพโครงสร้างพื้นฐานด้านไอที เราช่วยคุณลดต้นทุน เพิ่มศักยภาพให้กับทีม และปกป้องข้อมูลอันมีค่าของคุณ</p>
                    <div class="chart-container h-80 md:h-96">
                        <canvas id="impactChart-th"></canvas>
                    </div>
                </section>

                <section class="bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-2">การขับเคลื่อนการเติบโตอย่างยั่งยืน</h2>
                     <p class="text-center text-gray-600 mb-6">สภาพแวดล้อมไอทีที่ทันสมัยไม่ได้เป็นเพียงเรื่องของประสิทธิภาพเท่านั้น แต่ยังเป็นตัวขับเคลื่อนการเติบโตอีกด้วย ลูกค้าของเรามีการเติบโตของรายได้เพิ่มขึ้นอย่างต่อเนื่องหลังจากการใช้กลยุทธ์ของเรา</p>
                    <div class="chart-container h-80 md:h-96">
                        <canvas id="growthChart-th"></canvas>
                    </div>
                </section>

                <section class="md:col-span-2 bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-4">ความเป็นเลิศในทุกด้าน</h2>
                    <p class="text-center text-gray-600 mb-8 max-w-4xl mx-auto">เราภาคภูมิใจที่ได้มอบบริการที่ครอบคลุมและมีคุณภาพสูง ผลสำรวจความพึงพอใจของลูกค้าสะท้อนถึงความมุ่งมั่นของเราในเรื่องความเชี่ยวชาญ การสื่อสาร การตรงต่อเวลา และการมอบผลตอบแทนจากการลงทุน</p>
                    <div class="chart-container h-80 md:h-96 max-w-md">
                        <canvas id="satisfactionChart-th"></canvas>
                    </div>
                </section>
            </main>
        </div>

        <div id="th-content" class="hidden">
            <header class="text-center mb-12">
                <h1 class="text-4xl md:text-5xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-[#FF8F00] to-[#2ECC71] mb-2">จัด ว่า ดี ไอที คอนเซาท์ติ้ง</h1>
                <p class="text-xl md:text-2xl font-semibold">พลิกโฉมธุรกิจของคุณด้วยเทคโนโลยี</p>
                <p class="mt-2 text-gray-600 max-w-3xl mx-auto">ในยุคดิจิทัลที่เปลี่ยนแปลงอย่างรวดเร็ว ระบบไอทีที่ไม่มีประสิทธิภาพอาจเป็นอุปสรรคสำคัญต่อการเติบโต มาค้นพบว่าการให้คำปรึกษาด้านไอทีเชิงกลยุทธ์จะช่วยปรับปรุงการดำเนินงาน เพิ่มประสิทธิภาพ และขับเคลื่อนความสำเร็จได้อย่างไร</p>
            </header>

            <main class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <section class="md:col-span-2 bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-4">ต้นทุนที่มองไม่เห็นของระบบไอทีที่ล้าสมัย</h2>
                    <p class="text-center text-gray-600 mb-8 max-w-4xl mx-auto">ธุรกิจจำนวนมากประเมินค่าใช้จ่ายที่มองไม่เห็นจากการทำงานของระบบที่ไม่มีประสิทธิภาพต่ำเกินไป ปัญหาเล็กๆ น้อยๆ ที่เกิดขึ้นทุกวันเหล่านี้สะสมจนกลายเป็นความสูญเสียครั้งใหญ่ในแต่ละปี</p>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
                        <div>
                            <h3 class="text-xl font-semibold text-center mb-2">เวลาที่สูญเสียไปอยู่ที่ไหน?</h3>
                            <div class="chart-container h-64 md:h-80">
                                <canvas id="timeWastedChart-th"></canvas>
                            </div>
                        </div>
                        <div class="text-center">
                            <div class="kpi-card text-white p-8 rounded-xl shadow-lg">
                                <p class="text-lg font-semibold">เวลาเฉลี่ยที่สูญเสียต่อปี</p>
                                <p class="text-6xl font-bold my-2">250</p>
                                <p class="text-lg">ต่อพนักงาน</p>
                            </div>
                            <p class="mt-4 text-gray-600">ซึ่งเทียบเท่ากับการสูญเสียประสิทธิภาพการทำงานกว่า 6 สัปดาห์ต่อพนักงานหนึ่งคนในแต่ละปี ส่งผลกระทบโดยตรงต่อผลกำไรและความสามารถในการสร้างสรรค์นวัตกรรมของคุณ</p>
                        </div>
                    </div>
                </section>

                <section class="md:col-span-2 bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-6">เส้นทางสู่ความทันสมัยที่เราพิสูจน์แล้ว</h2>
                    <p class="text-center text-gray-600 mb-8 max-w-4xl mx-auto">เราใช้กระบวนการ 4 ขั้นตอนที่มีโครงสร้างชัดเจน เพื่อให้การเปลี่ยนแปลงทางดิจิทัลเป็นไปอย่างราบรื่นและประสบความสำเร็จ เป้าหมายของเราคือการทำความเข้าใจความท้าทายเฉพาะของธุรกิจคุณ และนำโซลูชันที่ปรับแต่งมาโดยเฉพาะไปใช้</p>
                    <div class="flex flex-col md:flex-row justify-around items-center space-y-6 md:space-y-0 md:space-x-4">
                        <div class="flex items-center flex-col text-center w-52">
                            <div class="bg-[#FFC700] text-white rounded-full w-20 h-20 flex items-center justify-center text-3xl font-bold shadow-md">1</div>
                            <h3 class="text-lg font-semibold mt-3">ประเมิน</h3>
                            <p class="text-sm text-gray-500">เราจะเจาะลึกเข้าไปในระบบปัจจุบันของคุณเพื่อระบุจุดที่ต้องแก้ไขและโอกาสในการพัฒนา</p>
                        </div>
                        <div class="text-3xl text-gray-300 hidden md:block">&rarr;</div>
                        <div class="flex items-center flex-col text-center w-52">
                            <div class="bg-[#FF8F00] text-white rounded-full w-20 h-20 flex items-center justify-center text-3xl font-bold shadow-md">2</div>
                            <h3 class="text-lg font-semibold mt-3">วางแผน</h3>
                            <p class="text-sm text-gray-500">เราจะพัฒนากลยุทธ์เฉพาะบุคคลพร้อมเป้าหมายที่ชัดเจน กำหนดเวลาและงบประมาณ</p>
                        </div>
                        <div class="text-3xl text-gray-300 hidden md:block">&rarr;</div>
                        <div class="flex items-center flex-col text-center w-52">
                            <div class="bg-[#2ECC71] text-white rounded-full w-20 h-20 flex items-center justify-center text-3xl font-bold shadow-md">3</div>
                            <h3 class="text-lg font-semibold mt-3">นำไปใช้</h3>
                            <p class="text-sm text-gray-500">ผู้เชี่ยวชาญของเราจะนำโซลูชันใหม่ๆ ไปใช้โดยสร้างความติดขัดให้น้อยที่สุดต่อธุรกิจของคุณ</p>
                        </div>
                         <div class="text-3xl text-gray-300 hidden md:block">&rarr;</div>
                        <div class="flex items-center flex-col text-center w-52">
                            <div class="bg-[#34495E] text-white rounded-full w-20 h-20 flex items-center justify-center text-3xl font-bold shadow-md">4</div>
                            <h3 class="text-lg font-semibold mt-3">สนับสนุน</h3>
                            <p class="text-sm text-gray-500">เราให้การสนับสนุนอย่างต่อเนื่องเพื่อให้ระบบของคุณทำงานได้อย่างราบรื่น</p>
                        </div>
                    </div>
                </section>

                <section class="bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-2">ผลกระทบจาก "จัด ว่า ดี"</h2>
                    <p class="text-center text-gray-600 mb-6">โซลูชันของเราช่วยสร้างการพัฒนาที่จับต้องได้ในตัวชี้วัดทางธุรกิจที่สำคัญ ด้วยการเพิ่มประสิทธิภาพโครงสร้างพื้นฐานด้านไอที เราช่วยคุณลดต้นทุน เพิ่มศักยภาพให้กับทีม และปกป้องข้อมูลอันมีค่าของคุณ</p>
                    <div class="chart-container h-80 md:h-96">
                        <canvas id="impactChart-th"></canvas>
                    </div>
                </section>

                <section class="bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-2">การขับเคลื่อนการเติบโตอย่างยั่งยืน</h2>
                     <p class="text-center text-gray-600 mb-6">สภาพแวดล้อมไอทีที่ทันสมัยไม่ได้เป็นเพียงเรื่องของประสิทธิภาพเท่านั้น แต่ยังเป็นตัวขับเคลื่อนการเติบโตอีกด้วย ลูกค้าของเรามีการเติบโตของรายได้เพิ่มขึ้นอย่างต่อเนื่องหลังจากการใช้กลยุทธ์ของเรา</p>
                    <div class="chart-container h-80 md:h-96">
                        <canvas id="growthChart-th"></canvas>
                    </div>
                </section>

                <section class="md:col-span-2 bg-white rounded-lg shadow-md p-6">
                    <h2 class="text-2xl font-bold text-center mb-4">ความเป็นเลิศในทุกด้าน</h2>
                    <p class="text-center text-gray-600 mb-8 max-w-4xl mx-auto">เราภาคภูมิใจที่ได้มอบบริการที่ครอบคลุมและมีคุณภาพสูง ผลสำรวจความพึงพอใจของลูกค้าสะท้อนถึงความมุ่งมั่นของเราในเรื่องความเชี่ยวชาญ การสื่อสาร การตรงต่อเวลา และการมอบผลตอบแทนจากการลงทุน</p>
                    <div class="chart-container h-80 md:h-96 max-w-md">
                        <canvas id="satisfactionChart-th"></canvas>
                    </div>
                </section>
            </main>
        </div>

        <footer class="text-center mt-12 py-6 border-t border-gray-200">
            <p id="footer-text" class="text-gray-600">&copy; 2025 Jad Wa Dee IT Consulting. All Rights Reserved.</p>
        </footer>

    </div>

    <script>
        const wrapLabel = (str, maxWidth) => {
            if (str.length <= maxWidth) {
                return str;
            }
            const words = str.split(' ');
            let lines = [];
            let currentLine = '';
            words.forEach(word => {
                if ((currentLine + word).length > maxWidth) {
                    lines.push(currentLine.trim());
                    currentLine = '';
                }
                currentLine += word + ' ';
            });
            lines.push(currentLine.trim());
            return lines;
        };

        const tooltipConfig = {
            plugins: {
                tooltip: {
                    callbacks: {
                        title: function(tooltipItems) {
                            const item = tooltipItems[0];
                            let label = item.chart.data.labels[item.dataIndex];
                            if (Array.isArray(label)) {
                              return label.join(' ');
                            } else {
                              return label;
                            }
                        }
                    }
                }
            }
        };

        const chartColors = {
            yellow: '#FFC700',
            orange: '#FF8F00',
            green: '#2ECC71',
            dark: '#34495E',
            light: '#F4F6F7'
        };

        const enLabels = {
            timeWasted: ['Manual Data Entry', 'Searching for Documents', 'System Downtime', 'Repetitive Admin Tasks'],
            impact: ['Operational Costs', 'Employee Productivity', 'Data Security Incidents'],
            growth: ['Q1', 'Q2', 'Q3', 'Q4', 'Q1 (Y2)'],
            satisfaction: ['Expertise', 'Communication', 'Timeliness', 'Ongoing Support', 'Return on Investment']
        };

        const thLabels = {
            timeWasted: ['การป้อนข้อมูลด้วยตนเอง', 'การค้นหาเอกสาร', 'ระบบล่ม', 'งานธุรการที่ซ้ำซาก'],
            impact: ['ค่าใช้จ่ายในการดำเนินงาน', 'ประสิทธิภาพการทำงานของพนักงาน', 'เหตุการณ์ด้านความปลอดภัยของข้อมูล'],
            growth: ['ไตรมาส 1', 'ไตรมาส 2', 'ไตรมาส 3', 'ไตรมาส 4', 'ไตรมาส 1 (ปี 2)'],
            satisfaction: ['ความเชี่ยวชาญ', 'การสื่อสาร', 'ตรงต่อเวลา', 'การสนับสนุนอย่างต่อเนื่อง', 'ผลตอบแทนจากการลงทุน']
        };

        let charts = {};

        function createCharts(lang) {
            const labels = lang === 'en' ? enLabels : thLabels;

            if (charts['timeWasted']) charts['timeWasted'].destroy();
            const timeWastedCtx = document.getElementById(`timeWastedChart-${lang}`).getContext('2d');
            charts['timeWasted'] = new Chart(timeWastedCtx, {
                type: 'doughnut',
                data: {
                    labels: labels.timeWasted,
                    datasets: [{
                        label: 'Time Wasted',
                        data: [40, 30, 20, 10],
                        backgroundColor: [chartColors.orange, chartColors.yellow, chartColors.dark, chartColors.green],
                        borderColor: '#ffffff',
                        borderWidth: 4,
                        hoverOffset: 4
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    plugins: {
                        legend: {
                            position: 'bottom',
                        },
                        tooltip: tooltipConfig.plugins.tooltip
                    }
                }
            });

            if (charts['impact']) charts['impact'].destroy();
            const impactCtx = document.getElementById(`impactChart-${lang}`).getContext('2d');
            charts['impact'] = new Chart(impactCtx, {
                type: 'bar',
                data: {
                    labels: labels.impact,
                    datasets: [{
                        label: 'ก่อน',
                        data: [100, 65, 20],
                        backgroundColor: 'rgba(52, 73, 94, 0.5)',
                        borderColor: chartColors.dark,
                        borderWidth: 1
                    }, {
                        label: 'หลัง',
                        data: [70, 95, 2],
                        backgroundColor: 'rgba(46, 204, 113, 0.7)',
                        borderColor: chartColors.green,
                        borderWidth: 1
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                     scales: {
                        y: {
                            beginAtZero: true,
                            ticks: {
                               callback: function(value, index, values) {
                                   return value + '%';
                               }
                            }
                        }
                    },
                    plugins: {
                        legend: {
                            position: 'top',
                        },
                        tooltip: tooltipConfig.plugins.tooltip
                    }
                }
            });

            if (charts['growth']) charts['growth'].destroy();
            const growthCtx = document.getElementById(`growthChart-${lang}`).getContext('2d');
            charts['growth'] = new Chart(growthCtx, {
                type: 'line',
                data: {
                    labels: labels.growth,
                    datasets: [{
                        label: 'Client Revenue Growth',
                        data: [0, 5, 9, 15, 22],
                        fill: true,
                        backgroundColor: 'rgba(255, 143, 0, 0.2)',
                        borderColor: chartColors.orange,
                        tension: 0.4,
                        pointBackgroundColor: chartColors.orange,
                        pointRadius: 5
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    scales: {
                        y: {
                            beginAtZero: true,
                            ticks: {
                               callback: function(value, index, values) {
                                   return value + '%';
                               }
                            }
                        }
                    },
                    plugins: {
                        legend: {
                            display: false
                        },
                        tooltip: tooltipConfig.plugins.tooltip
                    }
                }
            });

            if (charts['satisfaction']) charts['satisfaction'].destroy();
            const satisfactionCtx = document.getElementById(`satisfactionChart-${lang}`).getContext('2d');
            charts['satisfaction'] = new Chart(satisfactionCtx, {
                type: 'radar',
                data: {
                    labels: labels.satisfaction,
                    datasets: [{
                        label: 'คะแนนความพึงพอใจของลูกค้า (เต็ม 5)',
                        data: [4.8, 4.9, 4.6, 4.7, 4.9],
                        fill: true,
                        backgroundColor: 'rgba(46, 204, 113, 0.2)',
                        borderColor: chartColors.green,
                        pointBackgroundColor: chartColors.green,
                        pointBorderColor: '#fff',
                        pointHoverBackgroundColor: '#fff',
                        pointHoverBorderColor: chartColors.green
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    scales: {
                        r: {
                            angleLines: {
                                display: true
                            },
                            suggestedMin: 0,
                            suggestedMax: 5,
                            pointLabels: {
                                font: {
                                    size: 12
                                }
                            }
                        }
                    },
                    plugins: {
                        legend: {
                            position: 'top',
                        },
                        tooltip: tooltipConfig.plugins.tooltip
                    }
                }
            });
        }

        const enContent = document.getElementById('en-content');
        const thContent = document.getElementById('th-content');
        const footerText = document.getElementById('footer-text');
        const langThBtn = document.getElementById('lang-th');
        const langEnBtn = document.getElementById('lang-en');

        function setLanguage(lang) {
            if (lang === 'en') {
                enContent.classList.remove('hidden');
                thContent.classList.add('hidden');
                footerText.innerText = '© 2025 Jad Wa Dee IT Consulting. All Rights Reserved.';
                langEnBtn.classList.add('bg-[#2ECC71]');
                langEnBtn.classList.remove('bg-gray-400');
                langThBtn.classList.add('bg-gray-400');
                langThBtn.classList.remove('bg-[#FF8F00]');
                createCharts('en');
            } else {
                enContent.classList.add('hidden');
                thContent.classList.remove('hidden');
                footerText.innerText = '© 2025 จัด ว่า ดี ไอที คอนเซาท์ติ้ง. สงวนลิขสิทธิ์';
                langThBtn.classList.add('bg-[#FF8F00]');
                langThBtn.classList.remove('bg-gray-400');
                langEnBtn.classList.add('bg-gray-400');
                langEnBtn.classList.remove('bg-[#2ECC71]');
                createCharts('th');
            }
        }

        langThBtn.addEventListener('click', () => setLanguage('th'));
        langEnBtn.addEventListener('click', () => setLanguage('en'));

        setLanguage('th');
    </script>
</body>
</html>
