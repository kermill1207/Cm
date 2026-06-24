<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>세계관 가이드 & 커미션 자료</title>
    <style>
        :root {
            --c-base: #f8f9f8;
            --c-bg: #e2e2e2;
            --c-text: #060606;
            --c-border: #d0d0d0;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif, 'Apple SD Gothic Neo', 'Malgun Gothic';
            background-color: var(--c-bg);
            color: var(--c-text);
            display: flex;
            min-height: 100vh;
            overflow: hidden;
        }

        /* 수정 가능한 영역 강조 효과 */
        [contenteditable="true"] {
            padding: 2px 4px;
            border-radius: 4px;
            transition: background 0.2s;
            outline: none;
        }
        [contenteditable="true"]:hover, [contenteditable="true"]:focus {
            background-color: rgba(0, 0, 0, 0.05);
            box-shadow: 0 0 0 1px var(--c-border);
        }

        /* 기본 버튼 스타일 */
        .btn {
            background-color: var(--c-base);
            border: 1px solid var(--c-border);
            color: var(--c-text);
            padding: 6px 12px;
            border-radius: 4px;
            cursor: pointer;
            font-size: 0.85rem;
            transition: 0.2s;
        }
        .btn:hover { background-color: var(--c-bg); }
        .btn-primary { background-color: var(--c-text); color: var(--c-base); }
        .btn-primary:hover { background-color: #333; }
        .btn-danger { color: red; border-color: red; }
        .btn-danger:hover { background-color: #ffe6e6; }
        .del-btn {
            background: none; border: none; color: red; cursor: pointer;
            font-size: 0.8rem; margin-left: 5px; opacity: 0.5;
        }
        .del-btn:hover { opacity: 1; }

        /* 좌측 사이드바 */
        #sidebar {
            width: 260px;
            background-color: var(--c-base);
            border-right: 2px solid var(--c-border);
            padding: 30px 20px;
            display: flex;
            flex-direction: column;
            position: fixed;
            top: 0; bottom: 0; left: 0;
            z-index: 100;
        }
        #sidebar .logo {
            font-size: 1.1rem;
            font-weight: bold;
            margin-bottom: 40px;
            padding-left: 10px;
            border-left: 4px solid var(--c-text);
        }
        .menu-btn {
            background: none; border: none; color: var(--c-text);
            text-align: left; padding: 12px 15px; font-size: 0.95rem;
            cursor: pointer; border-radius: 6px; margin-bottom: 8px;
        }
        .menu-btn:hover { background-color: var(--c-bg); }
        .menu-btn.active { background-color: var(--c-text); color: var(--c-base); font-weight: bold; }

        /* 메인 콘텐츠 */
        #main-content {
            margin-left: 260px;
            flex: 1;
            padding: 40px;
            height: 100vh;
            overflow-y: auto;
        }
        .tab-content { display: none; max-width: 1100px; margin: 0 auto; }
        .tab-content.active { display: block; animation: fadeIn 0.3s ease; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(5px); } to { opacity: 1; transform: translateY(0); } }

        h1 { font-size: 1.8rem; margin-bottom: 20px; font-weight: 700; }
        .section-desc { color: #555; margin-bottom: 20px; line-height: 1.5; font-size: 0.95rem; }

        /* 카드 (세계관/명사) */
        .card {
            background-color: var(--c-base);
            border-radius: 8px; padding: 24px; margin-bottom: 24px;
            border: 1px solid var(--c-border);
        }

        /* 캐릭터 아카이브 관련 */
        .category-block { margin-bottom: 40px; }
        .category-header {
            display: flex; justify-content: space-between; align-items: center;
            border-bottom: 2px solid var(--c-text); padding-bottom: 10px; margin-bottom: 20px;
        }
        .category-title { font-size: 1.4rem; font-weight: bold; }
        
        .character-grid {
            display: grid; grid-template-columns: repeat(auto-fill, minmax(280px, 1fr)); gap: 20px;
        }
        .char-card {
            background-color: var(--c-base); border: 1px solid var(--c-border);
            border-radius: 8px; padding: 20px; position: relative;
        }
        .char-img-box {
            width: 100%; height: 200px; background-color: var(--c-bg);
            border-radius: 4px; margin-bottom: 15px; display: flex;
            align-items: center; justify-content: center; overflow: hidden;
            position: relative; border: 1px dashed #aaa;
        }
        .char-img-box img { width: 100%; height: 100%; object-fit: cover; display: none; }
        .img-upload-label { cursor: pointer; color: #666; font-size: 0.9rem; text-align: center;}
        .img-upload-label input { display: none; }
        .remove-img-btn {
            position: absolute; top: 5px; right: 5px; background: rgba(0,0,0,0.5);
            color: white; border: none; padding: 2px 6px; border-radius: 4px;
            cursor: pointer; display: none; font-size: 0.8rem;
        }
        .char-name { font-size: 1.2rem; font-weight: bold; margin-bottom: 15px; display: block; border-bottom: 1px solid var(--c-bg); padding-bottom: 10px;}
        .char-meta-list { list-style: none; font-size: 0.9rem; line-height: 1.6; margin-bottom: 15px;}
        .char-meta-list li { margin-bottom: 6px; display: flex; align-items: flex-start; }
        .char-meta-list strong { min-width: 80px; display: inline-block; color: #444; }
        .char-meta-list .desc { flex: 1; }
        .char-actions { display: flex; justify-content: space-between; margin-top: 15px; }

        /* 인물 관계도 캔버스 */
        #relation-wrapper {
            position: relative; width: 100%; height: 600px;
            background-color: var(--c-base); border: 1px solid var(--c-border);
            border-radius: 8px; overflow: hidden;
        }
        #relation-svg { position: absolute; top: 0; left: 0; width: 100%; height: 100%; pointer-events: none; }
        .svg-text { pointer-events: auto; cursor: pointer; font-weight: bold; text-shadow: -1px -1px 0 #fff, 1px -1px 0 #fff, -1px 1px 0 #fff, 1px 1px 0 #fff; }
        .svg-text:hover { fill: blue; }
        
        .rel-node {
            position: absolute; background-color: var(--c-base); border: 2px solid var(--c-text);
            padding: 10px; border-radius: 8px; min-width: 120px; text-align: center;
            box-shadow: 2px 2px 5px rgba(0,0,0,0.1); user-select: none;
        }
        .rel-node .handle {
            cursor: grab; background-color: var(--c-bg); padding: 2px;
            margin: -10px -10px 10px -10px; border-radius: 6px 6px 0 0;
            font-size: 0.8rem; color: #555;
        }
        .rel-node .handle:active { cursor: grabbing; }
        .rel-node-name { font-weight: bold; margin-bottom: 10px; }
        .rel-node-actions { display: flex; justify-content: space-between; gap: 5px; }
        .rel-node-actions button { flex: 1; padding: 4px; font-size: 0.75rem; }

        .toolbar { margin-bottom: 15px; display: flex; gap: 10px; }
    </style>
</head>
<body>

    <nav id="sidebar">
        <div class="logo" contenteditable="true">작품 제목 (커미션용)</div>
        <div class="menu-group">
            <button class="menu-btn active" onclick="switchTab('world')">🌌 세계관 및 명사 가이드</button>
            <button class="menu-btn" onclick="switchTab('characters')">👥 캐릭터 아카이브</button>
            <button class="menu-btn" onclick="switchTab('narrative')">🔗 인물 관계도</button>
        </div>
        <div style="margin-top:auto; font-size:0.8rem; color:#666;">
            ※ 수정된 내용은 브라우저를 닫으면 초기화됩니다. 내용을 작성한 후 브라우저의 'PDF로 인쇄'를 활용하여 저장하세요.
        </div>
    </nav>

    <main id="main-content">
        
        <section id="world" class="tab-content active">
            <h1>세계관 및 고유 명사 안내</h1>
            <p class="section-desc">커미션 작업자분이 작품의 분위기와 배경을 쉽게 이해할 수 있도록 자유롭게 수정하여 작성해 주세요.</p>
            
            <div class="card" id="glossary-container">
                <div style="display:flex; justify-content:space-between; margin-bottom:15px;">
                    <h2 contenteditable="true">세계관 요약 및 고유 명사</h2>
                    <button class="btn btn-primary" onclick="addGlossaryItem()">+ 항목 추가</button>
                </div>
                <ul id="glossary-list" style="list-style:none;">
                    <li style="margin-bottom: 15px; padding-bottom:15px; border-bottom:1px solid var(--c-border);">
                        <strong contenteditable="true" style="display:block; font-size:1.1rem; margin-bottom:5px;">배경 시대상</strong>
                        <div contenteditable="true">현대 판타지 기반이며, 몬스터가 출몰하는 게이트가 열린 지 20년이 지난 세계입니다.</div>
                        <button class="del-btn" onclick="this.parentElement.remove()">항목 삭제</button>
                    </li>
                </ul>
            </div>
        </section>

        <section id="characters" class="tab-content">
            <div style="display:flex; justify-content:space-between; align-items:center; margin-bottom:20px;">
                <h1>캐릭터 아카이브</h1>
                <button class="btn btn-primary" onclick="addCategory()">+ 그룹(카테고리) 추가</button>
            </div>
            <p class="section-desc">캐릭터의 외형, 특징, 설정표를 관리합니다. 텍스트를 클릭해 수정하고 이미지를 업로드하세요.</p>
            
            <div id="categories-wrapper">
                <div class="category-block">
                    <div class="category-header">
                        <span class="category-title" contenteditable="true">주요 인물</span>
                        <div>
                            <button class="btn" onclick="addCharacter(this)">+ 캐릭터 추가</button>
                            <button class="btn btn-danger" onclick="if(confirm('이 카테고리를 삭제할까요?')) this.closest('.category-block').remove()">그룹 삭제</button>
                        </div>
                    </div>
                    <div class="character-grid">
                        </div>
                </div>
            </div>
        </section>

        <section id="narrative" class="tab-content">
            <h1>인물 관계도</h1>
            <p class="section-desc">노드를 추가하고 드래그하여 배치하세요. [연결] 버튼을 눌러 다른 노드를 클릭하면 관계선이 생성됩니다. 생성된 선의 텍스트를 클릭해 관계를 적거나 삭제할 수 있습니다.</p>
            
            <div class="toolbar">
                <button class="btn btn-primary" onclick="addNode()">+ 인물 노드 추가</button>
                <span id="connect-status" style="color:red; font-weight:bold; margin-left:15px; display:none;">연결할 다른 대상을 클릭하세요! (취소하려면 빈 곳 클릭)</span>
            </div>

            <div id="relation-wrapper" onclick="cancelConnect(event)">
                <svg id="relation-svg"></svg>
                </div>
        </section>

    </main>

    <script>
        // --- [ 탭 전환 로직 ] ---
        function switchTab(tabId) {
            document.querySelectorAll('.tab-content').forEach(c => c.classList.remove('active'));
            document.querySelectorAll('.menu-btn').forEach(b => b.classList.remove('active'));
            document.getElementById(tabId).classList.add('active');
            event.currentTarget.classList.add('active');
        }

        // --- [ 세계관 명사 로직 ] ---
        function addGlossaryItem() {
            const list = document.getElementById('glossary-list');
            const li = document.createElement('li');
            li.style = "margin-bottom: 15px; padding-bottom:15px; border-bottom:1px solid var(--c-border);";
            li.innerHTML = `
                <strong contenteditable="true" style="display:block; font-size:1.1rem; margin-bottom:5px;">새 명사/설정</strong>
                <div contenteditable="true">설명을 입력하세요.</div>
                <button class="del-btn" onclick="this.parentElement.remove()">항목 삭제</button>
            `;
            list.appendChild(li);
        }

        // --- [ 캐릭터 아카이브 로직 ] ---
        const charTemplate = `
            <div class="char-card">
                <div class="char-img-box">
                    <label class="img-upload-label">
                        <br>클릭하여<br>외형 참고 이미지 업로드
                        <input type="file" accept="image/*" onchange="uploadImage(this)">
                    </label>
                    <img src="" alt="캐릭터 이미지">
                    <button class="remove-img-btn" onclick="removeImage(this)">이미지 삭제</button>
                </div>
                <span class="char-name" contenteditable="true">캐릭터 이름</span>
                <ul class="char-meta-list">
                    <li><strong contenteditable="true">성별 / 나이:</strong> <span class="desc" contenteditable="true">미상</span> <button class="del-btn" onclick="this.parentElement.remove()">X</button></li>
                    <li><strong contenteditable="true">종합 등급:</strong> <span class="desc" contenteditable="true">A 등급</span> <button class="del-btn" onclick="this.parentElement.remove()">X</button></li>
                    <li><strong contenteditable="true">성향:</strong> <span class="desc" contenteditable="true">중립</span> <button class="del-btn" onclick="this.parentElement.remove()">X</button></li>
                    <li><strong contenteditable="true">클래스 분류:</strong> <span class="desc" contenteditable="true">전투 계열</span> <button class="del-btn" onclick="this.parentElement.remove()">X</button></li>
                    <li><strong contenteditable="true">고유 특성:</strong> <span class="desc" contenteditable="true">특성명 입력</span> <button class="del-btn" onclick="this.parentElement.remove()">X</button></li>
                    <li><strong contenteditable="true">특이사항:</strong> <span class="desc" contenteditable="true">주변에 버려진 쓰레기를 주워 자리를 깨끗하게 청소함</span> <button class="del-btn" onclick="this.parentElement.remove()">X</button></li>
                </ul>
                <div class="char-actions">
                    <button class="btn" onclick="addCharAttribute(this)">+ 속성 추가</button>
                    <button class="btn btn-danger" onclick="if(confirm('캐릭터를 삭제할까요?')) this.closest('.char-card').remove()">캐릭터 삭제</button>
                </div>
            </div>
        `;

        function addCategory() {
            const wrapper = document.getElementById('categories-wrapper');
            const div = document.createElement('div');
            div.className = 'category-block';
            div.innerHTML = `
                <div class="category-header">
                    <span class="category-title" contenteditable="true">새 소속/그룹</span>
                    <div>
                        <button class="btn" onclick="addCharacter(this)">+ 캐릭터 추가</button>
                        <button class="btn btn-danger" onclick="if(confirm('이 카테고리를 삭제할까요?')) this.closest('.category-block').remove()">그룹 삭제</button>
                    </div>
                </div>
                <div class="character-grid"></div>
            `;
            wrapper.appendChild(div);
            // 카테고리 추가 시 기본 캐릭터 1명 추가
            div.querySelector('.character-grid').innerHTML = charTemplate;
        }

        function addCharacter(btn) {
            const grid = btn.closest('.category-block').querySelector('.character-grid');
            grid.insertAdjacentHTML('beforeend', charTemplate);
        }

        function addCharAttribute(btn) {
            const list = btn.closest('.char-card').querySelector('.char-meta-list');
            const li = document.createElement('li');
            li.innerHTML = `<strong contenteditable="true">새 속성:</strong> <span class="desc" contenteditable="true">내용 입력</span> <button class="del-btn" onclick="this.parentElement.remove()">X</button>`;
            list.appendChild(li);
        }

        function uploadImage(input) {
            if (input.files && input.files[0]) {
                const reader = new FileReader();
                reader.onload = function(e) {
                    const box = input.closest('.char-img-box');
                    box.querySelector('label').style.display = 'none';
                    const img = box.querySelector('img');
                    img.src = e.target.result;
                    img.style.display = 'block';
                    box.querySelector('.remove-img-btn').style.display = 'block';
                }
                reader.readAsDataURL(input.files[0]);
            }
        }

        function removeImage(btn) {
            const box = btn.closest('.char-img-box');
            box.querySelector('img').style.display = 'none';
            box.querySelector('img').src = '';
            box.querySelector('label').style.display = 'block';
            box.querySelector('.remove-img-btn').style.display = 'none';
            box.querySelector('input[type="file"]').value = ""; // 리셋
        }

        // 초기 카테고리에 샘플 캐릭터 삽입
        document.querySelector('.character-grid').innerHTML = charTemplate;


        // --- [ 인물 관계도 로직 ] ---
        let nodeCount = 0;
        let links = []; // {from: id, to: id, label: string}
        let connectingFromId = null;

        function addNode() {
            nodeCount++;
            const id = 'rel-node-' + nodeCount;
            const wrapper = document.getElementById('relation-wrapper');
            
            const node = document.createElement('div');
            node.className = 'rel-node';
            node.id = id;
            node.style.left = '50px';
            node.style.top = '50px';
            node.innerHTML = `
                <div class="handle">드래그 이동</div>
                <div class="rel-node-name" contenteditable="true">인물 ${nodeCount}</div>
                <div class="rel-node-actions">
                    <button class="btn btn-primary" onclick="startConnect('${id}', event)">연결</button>
                    <button class="btn btn-danger" onclick="deleteNode('${id}')">X</button>
                </div>
            `;
            wrapper.appendChild(node);
            makeDraggable(node);
        }

        function deleteNode(id) {
            if(!confirm('노드를 삭제하시겠습니까?')) return;
            document.getElementById(id).remove();
            links = links.filter(l => l.from !== id && l.to !== id);
            renderLinks();
            if(connectingFromId === id) cancelConnect();
        }

        // 드래그 로직
        function makeDraggable(elmnt) {
            let pos1 = 0, pos2 = 0, pos3 = 0, pos4 = 0;
            elmnt.querySelector('.handle').onmousedown = dragMouseDown;

            function dragMouseDown(e) {
                e.preventDefault();
                pos3 = e.clientX;
                pos4 = e.clientY;
                document.onmouseup = closeDragElement;
                document.onmousemove = elementDrag;
            }
            function elementDrag(e) {
                e.preventDefault();
                pos1 = pos3 - e.clientX;
                pos2 = pos4 - e.clientY;
                pos3 = e.clientX;
                pos4 = e.clientY;
                elmnt.style.top = (elmnt.offsetTop - pos2) + "px";
                elmnt.style.left = (elmnt.offsetLeft - pos1) + "px";
                renderLinks(); // 이동할 때 선도 같이 렌더링
            }
            function closeDragElement() {
                document.onmouseup = null;
                document.onmousemove = null;
            }
        }

        // 연결 로직
        function startConnect(id, event) {
            event.stopPropagation();
            if (!connectingFromId) {
                connectingFromId = id;
                document.getElementById('connect-status').style.display = 'inline';
            } else {
                if (connectingFromId !== id) {
                    // 이미 존재하는 연결인지 확인
                    const exists = links.find(l => (l.from === connectingFromId && l.to === id) || (l.to === connectingFromId && l.from === id));
                    if(!exists) {
                        links.push({ from: connectingFromId, to: id, label: '관계 (클릭하여 수정)' });
                        renderLinks();
                    }
                }
                cancelConnect();
            }
        }

        function cancelConnect(event) {
            // 배경 클릭시 취소
            if(event && event.target.closest('.rel-node')) return;
            connectingFromId = null;
            document.getElementById('connect-status').style.display = 'none';
        }

        function renderLinks() {
            const svg = document.getElementById('relation-svg');
            svg.innerHTML = '';
            const wrapperRect = document.getElementById('relation-wrapper').getBoundingClientRect();

            links.forEach((link, index) => {
                const fNode = document.getElementById(link.from);
                const tNode = document.getElementById(link.to);
                if (!fNode || !tNode) return;

                const fRect = fNode.getBoundingClientRect();
                const tRect = tNode.getBoundingClientRect();

                const x1 = fRect.left + (fRect.width/2) - wrapperRect.left;
                const y1 = fRect.top + (fRect.height/2) - wrapperRect.top;
                const x2 = tRect.left + (tRect.width/2) - wrapperRect.left;
                const y2 = tRect.top + (tRect.height/2) - wrapperRect.top;

                // 선 그리기
                const line = document.createElementNS('http://www.w3.org/2000/svg', 'line');
                line.setAttribute('x1', x1);
                line.setAttribute('y1', y1);
                line.setAttribute('x2', x2);
                line.setAttribute('y2', y2);
                line.setAttribute('stroke', 'var(--c-text)');
                line.setAttribute('stroke-width', '2');
                svg.appendChild(line);

                // 텍스트 (관계 레이블) 그리기
                const text = document.createElementNS('http://www.w3.org/2000/svg', 'text');
                text.setAttribute('x', (x1+x2)/2);
                text.setAttribute('y', (y1+y2)/2 - 8);
                text.setAttribute('fill', 'var(--c-text)');
                text.setAttribute('font-size', '13px');
                text.setAttribute('text-anchor', 'middle');
                text.setAttribute('class', 'svg-text');
                text.textContent = link.label;
                
                // 텍스트 클릭 시 레이블 수정/삭제
                text.onclick = function(e) {
                    e.stopPropagation();
                    const newVal = prompt('관계를 입력하세요. (내용을 모두 지우면 연결이 삭제됩니다.)', link.label);
                    if (newVal === null) return;
                    if (newVal.trim() === '') {
                        links.splice(index, 1);
                    } else {
                        link.label = newVal;
                    }
                    renderLinks();
                };

                // 선을 가리지 않도록 텍스트 배경을 위한 꼼수 (Stroke 활용)
                const bgText = text.cloneNode(true);
                bgText.setAttribute('stroke', 'var(--c-base)');
                bgText.setAttribute('stroke-width', '4');
                bgText.setAttribute('stroke-linejoin', 'round');
                bgText.style.pointerEvents = 'none';
                
                svg.appendChild(bgText);
                svg.appendChild(text);
            });
        }
        
        // 초기 기본 노드 2개 생성
        addNode();
        addNode();
        document.getElementById('rel-node-2').style.left = '300px';

    </script>
</body>
</html>
