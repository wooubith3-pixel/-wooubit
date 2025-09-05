<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>우유빛의원 면접자 사전 질문지</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Noto+Sans+KR:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', 'Noto Sans KR', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-100 flex items-center justify-center min-h-screen p-4 sm:p-6 lg:p-8">
    <div class="w-full max-w-4xl mx-auto bg-white rounded-2xl shadow-lg p-6 sm:p-8 md:p-12">
        
        <!-- 헤더 -->
        <header class="text-center mb-10">
            <h1 class="text-3xl sm:text-4xl font-bold text-gray-800">우유빛의원 면접자 사전 질문지</h1>
            <p class="mt-4 text-base sm:text-lg text-gray-600 max-w-3xl mx-auto">
                안녕하세요. 우유빛의원 채용에 관심을 가지고 지원해주셔서 진심으로 감사드립니다.<br>
                본 질문지는 면접에 앞서 지원자님에 대해 조금 더 깊이 이해하고, 면접 시간을 보다 의미 있게 활용하기 위해 준비되었습니다.
            </p>
        </header>

        <!-- 질문 폼 -->
        <form name="pre-interview-questionnaire" method="POST" data-netlify="true" class="space-y-10">
            <input type="hidden" name="form-name" value="pre-interview-questionnaire" />

            <!-- 지원자 정보 -->
            <div class="border-b border-gray-200 pb-8">
                <div class="grid grid-cols-1 gap-x-6 gap-y-8 sm:grid-cols-3">
                    <div class="sm:col-span-1">
                        <label for="name" class="block text-lg font-semibold text-gray-800">이름</label>
                        <div class="mt-2">
                            <input type="text" name="name" id="name" autocomplete="name" class="block w-full rounded-lg border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 text-base p-3 transition duration-150 ease-in-out" required>
                        </div>
                    </div>

                    <div class="sm:col-span-1">
                        <label for="department" class="block text-lg font-semibold text-gray-800">지원부서</label>
                        <div class="mt-2">
                            <input type="text" name="department" id="department" class="block w-full rounded-lg border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 text-base p-3 transition duration-150 ease-in-out" required>
                        </div>
                    </div>

                    <div class="sm:col-span-1">
                        <label for="date" class="block text-lg font-semibold text-gray-800">작성일</label>
                        <div class="mt-2">
                            <input type="text" name="date" id="date" placeholder="YYYY-MM-DD" class="block w-full rounded-lg border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 text-base p-3 transition duration-150 ease-in-out" required>
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- 질문 섹션 -->
            <div class="space-y-8">
                
                <!-- 기본 사항 -->
                <div>
                    <h2 class="text-2xl font-semibold text-gray-700 border-b-2 border-indigo-500 pb-3 mb-6">기본 사항</h2>
                    <div class="space-y-8">
                        <!-- 질문 1 -->
                        <div>
                            <label for="q1" class="block text-lg font-semibold text-gray-800">1. 이전 회사를 그만두게 된 이유는 무엇인가요?</label>
                            <textarea id="q1" name="q1" rows="4" class="mt-3 block w-full rounded-lg border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 text-base p-4 transition duration-150 ease-in-out"></textarea>
                        </div>
                        <!-- 질문 2 -->
                        <div>
                            <label for="q2" class="block text-lg font-semibold text-gray-800">2. 본인의 장점을 객관적으로 설명해주세요.</label>
                            <textarea id="q2" name="q2" rows="4" class="mt-3 block w-full rounded-lg border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 text-base p-4 transition duration-150 ease-in-out"></textarea>
                        </div>
                        <!-- 질문 3 -->
                        <div>
                            <label for="q3" class="block text-lg font-semibold text-gray-800">3. 새로운 직장을 통해 기대하거나 바라는 점은 무엇인가요?</label>
                            <textarea id="q3" name="q3" rows="4" class="mt-3 block w-full rounded-lg border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 text-base p-4 transition duration-150 ease-in-out"></textarea>
                        </div>
                        <!-- 질문 4 -->
                        <div>
                            <label for="q4" class="block text-lg font-semibold text-gray-800">4. 당사까지 어떤 이동 수단을 이용하셨고, 시간은 얼마나 걸리셨나요?</label>
                            <textarea id="q4" name="q4" rows="2" class="mt-3 block w-full rounded-lg border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 text-base p-4 transition duration-150 ease-in-out"></textarea>
                        </div>
                    </div>
                </div>

                <!-- 이전 직장 정보 -->
                <div>
                    <h2 class="text-2xl font-semibold text-gray-700 border-b-2 border-indigo-500 pb-3 mb-6">이전 직장 정보</h2>
                    <div class="space-y-8">
                        <!-- 질문 5 -->
                        <div>
                            <label for="q5" class="block text-lg font-semibold text-gray-800">5. 전 직장의 주된 근무 시간은 어떠했나요?</label>
                            <textarea id="q5" name="q5" rows="2" class="mt-3 block w-full rounded-lg border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 text-base p-4 transition duration-150 ease-in-out"></textarea>
                        </div>
                        <!-- 질문 6 -->
                        <div>
                            <label for="q6" class="block text-lg font-semibold text-gray-800">6. 전 직장의 복리후생에 대해 알려주세요.</label>
                            <textarea id="q6" name="q6" rows="4" class="mt-3 block w-full rounded-lg border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 text-base p-4 transition duration-150 ease-in-out"></textarea>
                        </div>
                        <!-- 질문 7 -->
                        <div>
                            <label for="q7" class="block text-lg font-semibold text-gray-800">7. 연차 사용이나 초과 근무(OT) 발생 시 어떤 방식으로 처리되었나요?</label>
                            <textarea id="q7" name="q7" rows="3" class="mt-3 block w-full rounded-lg border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 text-base p-4 transition duration-150 ease-in-out"></textarea>
                        </div>
                        <!-- 질문 8 -->
                        <div>
                            <label for="q8" class="block text-lg font-semibold text-gray-800">8. 근무했던 회사 중 가장 아쉬웠던 경험이 있다면, 어떤 회사였고 그 이유는 무엇인가요?</label>
                            <textarea id="q8" name="q8" rows="4" class="mt-3 block w-full rounded-lg border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 text-base p-4 transition duration-150 ease-in-out"></textarea>
                        </div>
                    </div>
                </div>

                <!-- 직무 역량 및 가치관 -->
                <div>
                    <h2 class="text-2xl font-semibold text-gray-700 border-b-2 border-indigo-500 pb-3 mb-6">직무 역량 및 가치관</h2>
                    <div class="space-y-8">
                        <!-- 질문 9 -->
                        <div>
                            <label for="q9" class="block text-lg font-semibold text-gray-800">9. 지원하신 직무와 관련하여, 본인이 가진 핵심 역량과 그동안의 업무 경험에 대해 설명해주세요.</label>
                            <textarea id="q9" name="q9" rows="5" class="mt-3 block w-full rounded-lg border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 text-base p-4 transition duration-150 ease-in-out"></textarea>
                        </div>
                        <!-- 질문 10 -->
                        <div>
                            <label for="q10" class="block text-lg font-semibold text-gray-800">10. 본인의 경력 중 가장 자랑스럽거나 성공적이었던 경험은 무엇인가요?</label>
                            <textarea id="q10" name="q10" rows="5" class="mt-3 block w-full rounded-lg border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 text-base p-4 transition duration-150 ease-in-out"></textarea>
                        </div>
                         <!-- 질문 11 -->
                        <div>
                            <label for="q11" class="block text-lg font-semibold text-gray-800">11. 지원하신 분야에 대한 본인의 실무 능력은 어느 정도 수준이라고 생각하시나요?</label>
                            <textarea id="q11" name="q11" rows="4" class="mt-3 block w-full rounded-lg border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 text-base p-4 transition duration-150 ease-in-out"></textarea>
                        </div>
                        <!-- 질문 12 -->
                        <div>
                            <label for="q12" class="block text-lg font-semibold text-gray-800">12. 지원 가능한 다른 포지션이 있다면 무엇이며, 팀에 어떤 도움(어시스트)을 줄 수 있는지 본인의 능력을 바탕으로 작성해주세요.</label>
                            <textarea id="q12" name="q12" rows="4" class="mt-3 block w-full rounded-lg border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 text-base p-4 transition duration-150 ease-in-out"></textarea>
                        </div>
                    </div>
                </div>

                <!-- 일상 생활 및 능력 -->
                <div>
                    <h2 class="text-2xl font-semibold text-gray-700 border-b-2 border-indigo-500 pb-3 mb-6">일상 생활 및 능력</h2>
                    <div class="space-y-8">
                        <!-- 질문 13 -->
                        <div>
                            <label for="q13" class="block text-lg font-semibold text-gray-800">13. 업무 중 스트레스가 발생했을 때, 자신만의 해소 방법이 있다면 알려주세요.</label>
                            <textarea id="q13" name="q13" rows="4" class="mt-3 block w-full rounded-lg border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 text-base p-4 transition duration-150 ease-in-out"></textarea>
                        </div>
                        <!-- 질문 14 -->
                        <div>
                            <label class="block text-lg font-semibold text-gray-800">14. 컴퓨터 사용 능력 (엑셀, 워드, 파워포인트)을 '상', '중', '하'로 표현해주세요.</label>
                            <div class="mt-4 space-y-4">
                                <div class="flex items-center gap-x-8">
                                    <span class="w-24 text-base font-medium text-gray-900">Excel:</span>
                                    <div class="flex items-center gap-x-6">
                                        <div class="flex items-center"><input id="excel-high" name="excel" value="상" type="radio" class="h-4 w-4 border-gray-300 text-indigo-600 focus:ring-indigo-600"><label for="excel-high" class="ml-2 block text-sm font-medium text-gray-900">상</label></div>
                                        <div class="flex items-center"><input id="excel-mid" name="excel" value="중" type="radio" class="h-4 w-4 border-gray-300 text-indigo-600 focus:ring-indigo-600"><label for="excel-mid" class="ml-2 block text-sm font-medium text-gray-900">중</label></div>
                                        <div class="flex items-center"><input id="excel-low" name="excel" value="하" type="radio" class="h-4 w-4 border-gray-300 text-indigo-600 focus:ring-indigo-600"><label for="excel-low" class="ml-2 block text-sm font-medium text-gray-900">하</label></div>
                                    </div>
                                </div>
                                <div class="flex items-center gap-x-8">
                                    <span class="w-24 text-base font-medium text-gray-900">Word:</span>
                                    <div class="flex items-center gap-x-6">
                                        <div class="flex items-center"><input id="word-high" name="word" value="상" type="radio" class="h-4 w-4 border-gray-300 text-indigo-600 focus:ring-indigo-600"><label for="word-high" class="ml-2 block text-sm font-medium text-gray-900">상</label></div>
                                        <div class="flex items-center"><input id="word-mid" name="word" value="중" type="radio" class="h-4 w-4 border-gray-300 text-indigo-600 focus:ring-indigo-600"><label for="word-mid" class="ml-2 block text-sm font-medium text-gray-900">중</label></div>
                                        <div class="flex items-center"><input id="word-low" name="word" value="하" type="radio" class="h-4 w-4 border-gray-300 text-indigo-600 focus:ring-indigo-600"><label for="word-low" class="ml-2 block text-sm font-medium text-gray-900">하</label></div>
                                    </div>
                                </div>
                                <div class="flex items-center gap-x-8">
                                    <span class="w-24 text-base font-medium text-gray-900">PowerPoint:</span>
                                    <div class="flex items-center gap-x-6">
                                        <div class="flex items-center"><input id="ppt-high" name="ppt" value="상" type="radio" class="h-4 w-4 border-gray-300 text-indigo-600 focus:ring-indigo-600"><label for="ppt-high" class="ml-2 block text-sm font-medium text-gray-900">상</label></div>
                                        <div class="flex items-center"><input id="ppt-mid" name="ppt" value="중" type="radio" class="h-4 w-4 border-gray-300 text-indigo-600 focus:ring-indigo-600"><label for="ppt-mid" class="ml-2 block text-sm font-medium text-gray-900">중</label></div>
                                        <div class="flex items-center"><input id="ppt-low" name="ppt" value="하" type="radio" class="h-4 w-4 border-gray-300 text-indigo-600 focus:ring-indigo-600"><label for="ppt-low" class="ml-2 block text-sm font-medium text-gray-900">하</label></div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <!-- 질문 15 -->
                        <div>
                            <label for="q15" class="block text-lg font-semibold text-gray-800">15. 사용 가능한 디자인 프로그램과 그 능력을 '상', '중', '하'로 작성해주세요. (예: Photoshop - 상, Figma - 중)</label>
                            <textarea id="q15" name="q15" rows="3" class="mt-3 block w-full rounded-lg border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 text-base p-4 transition duration-150 ease-in-out"></textarea>
                        </div>
                        <!-- 질문 16 -->
                        <div>
                            <label for="q16" class="block text-lg font-semibold text-gray-800">16. 가능한 언어적 능력(외국어 등)에 대해 작성해주세요.</label>
                            <textarea id="q16" name="q16" rows="3" class="mt-3 block w-full rounded-lg border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 text-base p-4 transition duration-150 ease-in-out"></textarea>
                        </div>
                        <!-- 질문 17 -->
                        <div>
                            <label for="q17" class="block text-lg font-semibold text-gray-800">17. 주량 및 흡연 여부에 대해 작성해주세요.</label>
                            <textarea id="q17" name="q17" rows="2" class="mt-3 block w-full rounded-lg border-gray-300 shadow-sm focus:border-indigo-500 focus:ring-indigo-500 text-base p-4 transition duration-150 ease-in-out"></textarea>
                        </div>
                    </div>
                </div>
            </div>

            <!-- 제출 버튼 -->
            <div class="pt-6 text-center">
                <button type="submit" class="inline-flex justify-center py-3 px-12 border border-transparent shadow-lg text-lg font-semibold rounded-full text-white bg-indigo-600 hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500 transition-transform transform hover:scale-105">
                    제출하기
                </button>
                <p class="mt-4 text-sm text-gray-500">작성해주셔서 감사합니다.</p>
            </div>
        </form>
    </div>
</body>
</html>

