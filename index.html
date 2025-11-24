<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Planner Holístico Ultimate</title>
    
    <!-- Bibliotecas Externas -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@latest/dist/umd/lucide.js"></script>
    
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&display=swap');
        
        body { 
           font-family: 'Poppins', sans-serif; 
           background-color: #F3F4F6; 
           color: #1F2937; 
           user-select: none; 
           overflow-x: hidden;
           padding-bottom: 120px;
        }
        
        /* Cores Will Bank */
        .bg-will-yellow { background-color: #FFEA00; }
        .text-will-yellow { color: #FFEA00; }
        .border-will-yellow { border-color: #FFEA00; }

        /* Animações */
        .screen-section { display: none; animation: slideUp 0.4s cubic-bezier(0.16, 1, 0.3, 1); }
        .screen-section.active { display: block; }
        
        @keyframes slideUp { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }
        @keyframes floatUp { 0% { opacity: 1; transform: translateY(0) scale(1); } 100% { opacity: 0; transform: translateY(-40px) scale(1.1); } }
        @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }

        .xp-float {
           position: absolute; font-weight: 800; color: #FFEA00;
           text-shadow: 0px 2px 4px rgba(0,0,0,0.3); pointer-events: none;
           animation: floatUp 1.2s ease-out forwards; z-index: 1000; font-size: 1.2rem;
        }

        /* UI Components */
        .nav-item { transition: all 0.3s; border-radius: 16px; }
        .nav-item.active { background-color: #111827; color: #FFEA00; transform: translateY(-4px); box-shadow: 0 4px 12px rgba(0,0,0,0.1); }
        .nav-item:not(.active) { color: #9CA3AF; }
        
        .wheel-score-input {
           width: 50px; height: 50px; border-radius: 16px; text-align: center;
           font-size: 1.2rem; font-weight: 700; border: 3px solid #E5E7EB; outline: none;
           background-color: #fff; transition: all 0.2s;
        }
        .wheel-score-input:focus { border-color: #111827; background-color: #FFFBEB; }
        
        .btn-primary {
           background-color: #FFEA00; color: #111827; font-weight: 700; border-radius: 99px;
           transition: transform 0.1s; box-shadow: 0 4px 0 #EAB308;
        }
        .btn-primary:active { transform: translateY(4px); box-shadow: 0 0 0 #EAB308; }

        .gamified-checkbox {
           width: 24px; height: 24px; border: 3px solid #D1D5DB; border-radius: 8px; cursor: pointer;
           display: flex; align-items: center; justify-content: center; transition: all 0.2s;
        }
        .gamified-checkbox.checked { background-color: #FFEA00; border-color: #111827; transform: scale(1.1); }

        .habit-grid { display: grid; grid-template-columns: 80px repeat(7, 1fr); gap: 4px; align-items: center; }
        .habit-btn { height: 32px; border-radius: 8px; display: flex; align-items: center; justify-content: center; font-weight: 700; font-size: 0.75rem; transition: all 0.2s; cursor: pointer; }
        .habit-btn.done { background-color: #111827; color: #FFEA00; }
        .habit-btn.pending { background-color: #E5E7EB; color: #9CA3AF; }

        .day-tab { padding: 8px 16px; border-radius: 12px; font-size: 0.75rem; font-weight: 600; color: #6B7280; cursor: pointer; white-space: nowrap; background-color: white; border: 1px solid #E5E7EB; transition: all 0.2s; display: flex; flex-direction: column; align-items: center; justify-content: center; min-width: 60px; }
        .day-tab span.date { font-size: 0.65rem; opacity: 0.7; font-weight: 400; margin-top: 2px; }
        .day-tab.active { background-color: #111827; color: #FFEA00; border-color: #111827; transform: scale(1.05); }

        .badge-card {
           background: linear-gradient(135deg, #ffffff 0%, #f3f4f6 100%); border: 1px solid #e5e7eb; opacity: 0.5; filter: grayscale(1); transition: all 0.3s; position: relative; overflow: hidden;
        }
        .badge-card.unlocked { opacity: 1; filter: grayscale(0); border-color: #FFEA00; background: white; box-shadow: 0 4px 15px rgba(255, 234, 0, 0.15); }
        .badge-ribbon { position: absolute; top: 0; right: 0; background: #FFEA00; color: #000; font-size: 0.6rem; font-weight: bold; padding: 2px 6px; border-bottom-left-radius: 8px; }

        .progress-bar { height: 8px; background-color: #E5E7EB; border-radius: 99px; overflow: hidden; }
        .progress-fill { height: 100%; background-color: #111827; transition: width 0.5s ease-out; }

        .heatmap-box { width: 100%; padding-top: 100%; border-radius: 6px; position: relative; background-color: #E5E7EB; transition: all 0.3s; }
        .heatmap-box.lvl-0 { background-color: #374151; opacity: 0.2; }
        .heatmap-box.lvl-1 { background-color: #FEF08A; }
        .heatmap-box.lvl-2 { background-color: #FDE047; } 
        .heatmap-box.lvl-3 { background-color: #EAB308; } 
        .heatmap-box.lvl-4 { background-color: #FFEA00; box-shadow: 0 0 8px rgba(255, 234, 0, 0.6); }

        /* Modais */
        #suggestionModal, #missionModal { background-color: rgba(0,0,0,0.8); backdrop-filter: blur(4px); z-index: 9999; animation: fadeIn 0.3s; }
        
        .filter-btn { padding: 4px 12px; border-radius: 99px; font-size: 0.75rem; font-weight: 700; border: 1px solid transparent; transition: all 0.2s; }
        .filter-btn.active { background-color: #FFEA00; color: #000; border-color: #000; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
        .filter-btn.inactive { background-color: white; color: #9CA3AF; border-color: #E5E7EB; }

        .target-dot { cursor: pointer; transition: all 0.3s; }
        .target-dot:hover { r: 6; stroke-width: 2; stroke: white; }
    </style>
    
    <script type="module">
        import { initializeApp } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-app.js";
        import { getAuth, signInAnonymously, signInWithCustomToken, onAuthStateChanged } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-auth.js";
        import { getFirestore, doc, setDoc, onSnapshot, collection, deleteDoc } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-firestore.js";

        // --- CONSTANTES ---
        const LEVELS = [
            { threshold: 0, name: "O Desligado", color: "text-gray-400" },
            { threshold: 2500, name: "Iniciante Intencional", color: "text-yellow-600" },
            { threshold: 7000, name: "Praticante Consciente", color: "text-blue-600" },
            { threshold: 15000, name: "Mestre da Rotina", color: "text-purple-600" },
            { threshold: 30000, name: "Equilibrador Lendário", color: "text-will-yellow" }
        ];

        const CHALLENGES = [
            { id: 'c_meditation', name: 'Monge Despertador', tag: 'meditation_21', target: 21, icon: '🧘', desc: '21 dias de Meditação (8h40)' },
            { id: 'c_gym', name: 'Maromba na Madruga', tag: 'gym_21', target: 21, icon: '💪', desc: '21 dias de Treino (7h30)' },
            { id: 'c_gratitude', name: 'Jornada Gratidão', tag: 'gratitude_21', target: 21, icon: '🙏', desc: '21 dias de Gratidão Matinal' },
            { id: 'c_fasting', name: 'Fim de Jejum Perfeito', tag: 'fasting_21', target: 21, icon: '🥑', desc: '21 dias de Crepioca (Seg-Sex)' }
        ];

        const BADGES = [
            { id: 'monge', name: 'O Monge', desc: 'Concluiu 21 dias Meditação', icon: '🧘', type: 'challenge', challengeId: 'c_meditation', xpBonus: 1500 },
            { id: 'maromba', name: 'Maromba', desc: 'Concluiu 21 dias Treino', icon: '🏋️', type: 'challenge', challengeId: 'c_gym', xpBonus: 1500 },
            { id: 'gratidao', name: 'Gratidão', desc: 'Concluiu 21 dias Gratidão', icon: '🙏', type: 'challenge', challengeId: 'c_gratitude', xpBonus: 1500 },
            { id: 'jejum', name: 'Jejum Pro', desc: 'Concluiu 21 dias Jejum', icon: '🥑', type: 'challenge', challengeId: 'c_fasting', xpBonus: 1500 },
            { id: 'rolezeiro', name: 'Rolezeiro(a) Raiz', desc: '4 Sábados Sociais', icon: '🎉', type: 'count_weekly', target: 4, tag: 'social_sat', xpBonus: 800 },
            { id: 'lazer_int', name: 'Lazer Intencional', desc: '10x Blocos Hobby', icon: '🎨', type: 'count_total', target: 10, tag: 'leisure_real', xpBonus: 600 },
            { id: 'profeta', name: 'O Profeta', desc: '4 Domingos Planejados', icon: '🔮', type: 'count_weekly', target: 4, tag: 'planning_sun', xpBonus: 1000 },
            { id: 'soneca', name: 'Soneca de Ouro', desc: '7 dias sono cumprido', icon: '😴', type: 'streak', target: 7, tag: 'sleep_7', xpBonus: 500 }
        ];

        const CATEGORIES_MAP = [
            { id: 'health', label: 'Saúde Física', wheelKey: 'saude', keywords: ['treino', 'academia', 'corrida', 'alongamento', 'ioga', 'médico', 'banho', 'skincare'] },
            { id: 'spirit', label: 'Espiritualidade', wheelKey: 'espiritualidade', keywords: ['terreiro', 'oração', 'ritual', 'igreja', 'fé'] },
            { id: 'work', label: 'Carreira/Finanças', wheelKey: 'carreira', keywords: ['trabalho', 'projeto', 'reunião', 'planilha', 'financeiro', 'e-mail'] },
            { id: 'study', label: 'Estudo/Intelecto', wheelKey: 'intelecto', keywords: ['estudar', 'ler', 'curso', 'inglês', 'livro', 'aprender', 'idioma'] },
            { id: 'mind', label: 'Saúde Mental', wheelKey: 'emocional', keywords: ['meditar', 'meditação', 'diário', 'terapia', 'respiração', 'emoção', 'gratidão'] },
            { id: 'food', label: 'Nutrição', wheelKey: 'saude', keywords: ['cozinhar', 'dieta', 'água', 'lanche', 'jejum', 'almoço', 'jantar', 'café'] },
            { id: 'leisure', label: 'Lazer/Social', wheelKey: 'lazer', keywords: ['lazer', 'série', 'filme', 'amigos', 'bar', 'social', 'rolê', 'descanso'] },
            { id: 'admin', label: 'Organização', wheelKey: 'carreira', keywords: ['casa', 'limpeza', 'mercado', 'organizar', 'planejar'] }, 
            { id: 'morning', label: 'Rotina Matinal', wheelKey: 'emocional', keywords: ['acordar', 'cama'] }, 
            { id: 'sleep', label: 'Descanso', wheelKey: 'saude', keywords: ['dormir', 'sono'] } 
        ];

        const WHEEL_COLORS = {
           'saude': '#10B981', 'carreira': '#3B82F6', 'financas': '#F59E0B', 'relacionamentos': '#EF4444',
           'lazer': '#EC4899', 'espiritualidade': '#8B5CF6', 'intelecto': '#6366F1', 'emocional': '#14B8A6'
        };

        const WEEKLY_ROUTINE = {
            0: [ // SEGUNDA
                { id: 'seg_morn', time: "7h - 7h20", title: "Café + Leitura", sub: "+ 2 min gratidão", cat: "morning", xpBase: 50, challengeTag: 'gratitude_21' },
                { id: 'seg_gym', time: "7h30 - 8h30", title: "Academia", cat: "health", xpBase: 100, challengeTag: 'gym_21' },
                { id: 'seg_med', time: "8h40 - 8h50", title: "Meditação", cat: "mind", xpBase: 100, challengeTag: 'meditation_21' },
                { id: 'seg_work', time: "9h - 18h", title: "Trabalho", cat: "work", xpBase: 50 },
                { id: 'seg_snack1', time: "10h", title: "Lanche 2", cat: "food", xpBase: 25 },
                { id: 'seg_lunch', time: "13h", title: "Almoço Low Carb", sub: "+ 5 min respiração", cat: "food", xpBase: 50 },
                { id: 'seg_snack2', time: "16h", title: "Chá + Torrada", cat: "food", xpBase: 25 },
                { id: 'seg_din', time: "18h30", title: "Crepioca + Jejum", cat: "food", xpBase: 50, challengeTag: 'fasting_21' },
                { id: 'seg_terr', time: "19h - 20h", title: "TERREIRO", sub: "+ Ritual Espiritual", cat: "spirit", xpBase: 100 },
                { id: 'seg_relax', time: "21h - 22h", title: "Relaxar / Série", cat: "leisure", xpBase: 50 },
                { id: 'seg_sleep', time: "~23h", title: "Skincare + Dormir", cat: "sleep", xpBase: 50, challengeTag: 'sleep_7' }
            ],
            1: [ // TERÇA
                { id: 'ter_morn', time: "7h - 7h20", title: "Café + Leitura", sub: "+ 2 min gratidão", cat: "morning", xpBase: 50, challengeTag: 'gratitude_21' },
                { id: 'ter_gym', time: "7h30 - 8h30", title: "Academia", cat: "health", xpBase: 100, challengeTag: 'gym_21' },
                { id: 'ter_med', time: "8h40 - 8h50", title: "Meditação", cat: "mind", xpBase: 100, challengeTag: 'meditation_21' },
                { id: 'ter_work', time: "9h - 18h", title: "Trabalho", cat: "work", xpBase: 50 },
                { id: 'ter_snack1', time: "10h", title: "Lanche 2", cat: "food", xpBase: 25 },
                { id: 'ter_lunch', time: "13h", title: "Almoço Low Carb", sub: "+ Pausa sensorial", cat: "food", xpBase: 50 },
                { id: 'ter_snack2', time: "16h", title: "Chá + Torrada", cat: "food", xpBase: 25 },
                { id: 'ter_din', time: "18h30", title: "Crepioca + Jejum", cat: "food", xpBase: 50, challengeTag: 'fasting_21' },
                { id: 'ter_stud', time: "19h30 - 20h30", title: "Estudo + Capilar", sub: "+ Máscara Detox", cat: "study", xpBase: 100, challengeTag: 'cronograma_capilar' },
                { id: 'ter_emo', time: "20h - 20h30", title: "Cuidado Emocional", sub: "Escrita ou respiração", cat: "mind", xpBase: 50 },
                { id: 'ter_fun', time: "21h - 22h", title: "Tempo de Prazer", sub: "Música, desenho, dança", cat: "leisure", xpBase: 50 },
                { id: 'ter_sleep', time: "~23h", title: "Skincare + Dormir", cat: "sleep", xpBase: 50, challengeTag: 'sleep_7' }
            ],
            2: [ // QUARTA
                { id: 'qua_morn', time: "7h - 7h20", title: "Café + Leitura", sub: "+ 2 min gratidão", cat: "morning", xpBase: 50, challengeTag: 'gratitude_21' },
                { id: 'qua_gym', time: "7h30 - 8h30", title: "Academia", cat: "health", xpBase: 100, challengeTag: 'gym_21' },
                { id: 'qua_med', time: "8h40 - 8h50", title: "Meditação", cat: "mind", xpBase: 100, challengeTag: 'meditation_21' },
                { id: 'qua_work', time: "9h - 18h", title: "Trabalho", cat: "work", xpBase: 50 },
                { id: 'qua_snack1', time: "10h", title: "Lanche 2", cat: "food", xpBase: 25 },
                { id: 'qua_lunch', time: "13h", title: "Almoço Low Carb", sub: "+ Pausa sensorial", cat: "food", xpBase: 50 },
                { id: 'qua_snack2', time: "16h", title: "Chá + Torrada", cat: "food", xpBase: 25 },
                { id: 'qua_din', time: "18h30", title: "Crepioca + Jejum", cat: "food", xpBase: 50, challengeTag: 'fasting_21' },
                { id: 'qua_stud', time: "19h30 - 20h30", title: "Estudo + Ritual", sub: "Mental leve", cat: "study", xpBase: 100 },
                { id: 'qua_relax', time: "21h - 22h", title: "Lazer Leve", sub: "Série, leitura", cat: "leisure", xpBase: 50 },
                { id: 'qua_sleep', time: "~23h", title: "Skincare + Dormir", cat: "sleep", xpBase: 50, challengeTag: 'sleep_7' }
            ],
            3: [ // QUINTA
                { id: 'qui_morn', time: "7h - 7h20", title: "Café + Leitura", sub: "+ 2 min gratidão", cat: "morning", xpBase: 50, challengeTag: 'gratitude_21' },
                { id: 'qui_gym', time: "7h30 - 8h30", title: "Academia", cat: "health", xpBase: 100, challengeTag: 'gym_21' },
                { id: 'qui_med', time: "8h40 - 8h50", title: "Meditação", cat: "mind", xpBase: 100, challengeTag: 'meditation_21' },
                { id: 'qui_work', time: "9h - 18h", title: "Trabalho", cat: "work", xpBase: 50 },
                { id: 'qui_snack1', time: "10h", title: "Lanche 2", cat: "food", xpBase: 25 },
                { id: 'qui_lunch', time: "13h", title: "Almoço Low Carb", sub: "+ Pausa sensorial", cat: "food", xpBase: 50 },
                { id: 'qui_snack2', time: "16h", title: "Chá + Torrada", cat: "food", xpBase: 25 },
                { id: 'qui_din', time: "18h30", title: "Crepioca + Jejum", cat: "food", xpBase: 50, challengeTag: 'fasting_21' },
                { id: 'qui_stud', time: "19h30 - 20h30", title: "Estudo + Capilar", sub: "+ Pausa emocional", cat: "study", xpBase: 100, challengeTag: 'cronograma_capilar' },
                { id: 'qui_emo', time: "20h - 20h30", title: "Cuidado Emocional", sub: "Respiração ou EFT", cat: "mind", xpBase: 50 },
                { id: 'qui_relax', time: "21h - 22h", title: "Lazer Leve", cat: "leisure", xpBase: 50 },
                { id: 'qui_sleep', time: "~23h", title: "Skincare + Dormir", cat: "sleep", xpBase: 50, challengeTag: 'sleep_7' }
            ],
            4: [ // SEXTA
                { id: 'sex_morn', time: "7h - 7h20", title: "Café + Leitura", sub: "+ 2 min gratidão", cat: "morning", xpBase: 50, challengeTag: 'gratitude_21' },
                { id: 'sex_gym', time: "7h30 - 8h30", title: "Academia", cat: "health", xpBase: 100, challengeTag: 'gym_21' },
                { id: 'sex_med', time: "8h40 - 8h50", title: "Meditação", cat: "mind", xpBase: 100, challengeTag: 'meditation_21' },
                { id: 'sex_work', time: "9h - 18h", title: "Trabalho", cat: "work", xpBase: 50 },
                { id: 'sex_snack1', time: "10h", title: "Lanche 2", cat: "food", xpBase: 25 },
                { id: 'sex_lunch', time: "13h", title: "Almoço Low Carb", sub: "+ Pausa sensorial", cat: "food", xpBase: 50 },
                { id: 'sex_snack2', time: "16h", title: "Chá + Torrada", cat: "food", xpBase: 25 },
                { id: 'sex_din', time: "18h30", title: "Crepioca + Jejum", cat: "food", xpBase: 50, challengeTag: 'fasting_21' },
                { id: 'sex_terr', time: "19h - 20h", title: "TERREIRO", sub: "+ Máscara facial", cat: "spirit", xpBase: 100, challengeTag: 'mascara_detox' },
                { id: 'sex_relax', time: "21h - 22h", title: "Relaxar Pós Terreiro", cat: "leisure", xpBase: 50 },
                { id: 'sex_sleep', time: "~23h", title: "Skincare + Dormir", cat: "sleep", xpBase: 50, challengeTag: 'sleep_7' }
            ],
            5: [ // SÁBADO
                { id: 'sab_morn', time: "7h - 7h20", title: "Café + Leitura", sub: "+ 2 min gratidão", cat: "morning", xpBase: 50, challengeTag: 'gratitude_21' },
                { id: 'sab_move', time: "7h30 - 8h30", title: "Treino Leve / Dança", cat: "health", xpBase: 50, challengeTag: 'gym_21' },
                { id: 'sab_med', time: "8h40 - 8h50", title: "Meditação Opcional", cat: "mind", xpBase: 50 },
                { id: 'sab_free', time: "9h - 18h", title: "Livre / Social", sub: "Barbacena (quinzenal)", cat: "leisure", xpBase: 100 },
                { id: 'sab_lunch', time: "13h", title: "Almoço Leve", cat: "food", xpBase: 25 },
                { id: 'sab_din', time: "18h30", title: "Jantar Leve", cat: "food", xpBase: 25 },
                { id: 'sab_hobby', time: "19h - 20h", title: "Social / Lazer Real", sub: "Filme, dança, rolê", cat: "leisure", xpBase: 100, challengeTag: 'leisure_real' },
                { id: 'sab_bath', time: "20h - 20h30", title: "Banho Relaxante", cat: "health", xpBase: 50 },
                { id: 'sab_party', time: "21h - 22h", title: "Vida Social / Rolê", cat: "leisure", xpBase: 50, challengeTag: 'social_sat' },
                { id: 'sab_sleep', time: "~23h", title: "Skincare + Dormir", cat: "sleep", xpBase: 50, challengeTag: 'sleep_7' }
            ],
            6: [ // DOMINGO
                { id: 'dom_morn', time: "7h - 7h20", title: "Café Leve", sub: "Gratidão + Intenção", cat: "morning", xpBase: 50, challengeTag: 'gratitude_21' },
                { id: 'dom_walk', time: "7h30 - 8h30", title: "Caminhada Feira", cat: "health", xpBase: 50, challengeTag: 'gym_21' },
                { id: 'dom_med', time: "8h40 - 8h50", title: "Meditação Leve", cat: "mind", xpBase: 50, challengeTag: 'meditation_21' },
                { id: 'dom_house', time: "9h - 18h", title: "Cozinhar / Casa", sub: "Mercado e Feira", cat: "admin", xpBase: 50 },
                { id: 'dom_lunch', time: "13h", title: "Almoço", cat: "food", xpBase: 25 },
                { id: 'dom_snack', time: "16h", title: "Lanche", cat: "food", xpBase: 25 },
                { id: 'dom_din', time: "18h30", title: "Jantar Leve", cat: "food", xpBase: 25 },
                { id: 'dom_plan', time: "19h - 20h", title: "Planejamento Semana", sub: "+ Finanças (quinz)", cat: "admin", xpBase: 100, challengeTag: 'planning_sun' },
                { id: 'dom_clean', time: "20h - 20h30", title: "Limpeza Energética", cat: "spirit", xpBase: 50 },
                { id: 'dom_rest', time: "21h - 22h", title: "Descanso Absoluto", cat: "leisure", xpBase: 50 },
                { id: 'dom_sleep', time: "~23h", title: "Skincare + Dormir", cat: "sleep", xpBase: 50, challengeTag: 'sleep_7' }
            ]
        };

        const CATEGORY_STYLES = {
           morning: "bg-yellow-100 text-yellow-900 border-l-4 border-yellow-500",
           health: "bg-green-100 text-green-900 border-l-4 border-green-500",
            mind: "bg-teal-100 text-teal-900 border-l-4 border-teal-500",
            work: "bg-blue-100 text-blue-900 border-l-4 border-blue-500",
            food: "bg-orange-100 text-orange-900 border-l-4 border-orange-500",
           spirit: "bg-purple-100 text-purple-900 border-l-4 border-purple-600",
           study: "bg-indigo-100 text-indigo-900 border-l-4 border-indigo-500",
           leisure: "bg-pink-100 text-pink-900 border-l-4 border-pink-500",
           admin: "bg-gray-200 text-gray-900 border-l-4 border-gray-600",
           sleep: "bg-slate-200 text-slate-700 border-l-4 border-slate-500",
        };

        // --- UTILITÁRIOS DE DATA ---
        const getLocalISODate = (d) => {
            const offset = d.getTimezoneOffset() * 60000;
            return new Date(d.getTime() - offset).toISOString().split('T')[0];
        };

        window.getTodayDateString = () => getLocalISODate(new Date());

        window.getDateStringForDay = (dayIndex) => {
            const date = new Date();
            const currentDayIndex = date.getDay() === 0 ? 6 : date.getDay() - 1; 
            date.setDate(date.getDate() + (dayIndex - currentDayIndex));
            return getLocalISODate(date);
        };

        window.getDateStringAgo = (daysAgo) => {
            const d = new Date(); 
            d.setDate(d.getDate() - daysAgo); 
            return getLocalISODate(d);
        };
        
        const getDaysDifference = (date1Str, date2Str) => {
            const d1 = new Date(date1Str);
            const d2 = new Date(date2Str);
            const diffTime = Math.abs(d2 - d1);
            return Math.ceil(diffTime / (1000 * 60 * 60 * 24)); 
        };

        window.getCurrentDayIndex = () => { const day = new Date().getDay(); return day === 0 ? 6 : day - 1; };

        // Variáveis de Estado
        let db, auth, currentUserId;
        let isAuthReady = false, isDomReady = false;
        let dailyData = {}, wheelData = {};
        let challengesStatus = {}; 
        let customTasksData = {}; 
        let selectedDayIndex = window.getCurrentDayIndex(); 
        let els = {}; 
        let pendingSuggestions = [];
        let evolutionPeriod = 7; 
        let currentEditingTaskId = null; 

        // --- FIREBASE SETUP ---
        const firebaseConfig = typeof __firebase_config !== 'undefined' ? JSON.parse(__firebase_config) : {};
        const appId = typeof __app_id !== 'undefined' ? __app_id : 'default-app';
        
        if (Object.keys(firebaseConfig).length > 0) {
            const app = initializeApp(firebaseConfig);
            db = getFirestore(app);
            auth = getAuth(app);
            onAuthStateChanged(auth, async (user) => {
                if (user) currentUserId = user.uid;
                else {
                   try { if (typeof __initial_auth_token !== 'undefined') await signInWithCustomToken(auth, __initial_auth_token); else await signInAnonymously(auth); currentUserId = auth.currentUser.uid; } catch(e) { console.error(e); currentUserId = 'offline-user'; }
                }
                isAuthReady = true; tryBootstrap();
            });
        } else { currentUserId = 'offline-demo'; isAuthReady = true; tryBootstrap(); }

        // --- LÓGICA DE DADOS ---
        function setupListeners() {
            if (!db || !currentUserId) return;
            onSnapshot(doc(db, `artifacts/${appId}/users/${currentUserId}/life_wheel`, 'weekly_data'), (docSnap) => {
                wheelData = docSnap.exists() ? docSnap.data() : { scores: {}, focusCategories: [], focus: "", review: {} };
                renderAll();
            });
            onSnapshot(doc(db, `artifacts/${appId}/users/${currentUserId}/life_wheel`, 'challenges_status'), (docSnap) => {
                challengesStatus = docSnap.exists() ? docSnap.data() : {};
                renderAll();
            });
            onSnapshot(collection(db, `artifacts/${appId}/users/${currentUserId}/daily_data`), (snap) => {
                dailyData = {};
                snap.forEach(d => dailyData[d.id] = d.data());
                renderAll();
            });
            onSnapshot(collection(db, `artifacts/${appId}/users/${currentUserId}/custom_tasks`), (snap) => {
                customTasksData = {};
                snap.forEach(d => customTasksData[d.id] = d.data());
                renderAll();
            });
        }

        // --- GESTÃO DE MISSÕES (CRUD) ---
        window.getSuggestedTime = (dayIndex) => {
            const staticTasks = WEEKLY_ROUTINE[dayIndex] || [];
            const customTasks = Object.values(customTasksData).filter(t => t.recurrenceDays && t.recurrenceDays.includes(dayIndex));
            const allTasks = [...staticTasks, ...customTasks];
            
            if (allTasks.length === 0) return "08:00 - 09:00";
            const getLastHour = (timeStr) => {
               const parts = timeStr.split('-');
               const endPart = parts.length > 1 ? parts[1] : parts[0];
               const clean = endPart.toLowerCase().replace('h', '.').replace(':', '.');
               return parseFloat(clean);
            };
            const sorted = allTasks.sort((a,b) => getLastHour(a.time) - getLastHour(b.time));
            const lastTask = sorted[sorted.length - 1];
            const lastHour = getLastHour(lastTask.time);
            
            if (!isNaN(lastHour)) {
               const nextStart = Math.floor(lastHour) + 1;
               return `${nextStart}h00 - ${nextStart + 1}h00`;
            }
            return "10:00 - 11:00";
        }

        window.suggestCategory = (title) => {
            const lowerTitle = title.toLowerCase();
            for (const cat of CATEGORIES_MAP) {
               if (cat.keywords && cat.keywords.some(k => lowerTitle.includes(k))) return cat.id;
            }
            return 'admin'; 
        }

        window.openMissionModal = (mode, taskId = null) => {
            currentEditingTaskId = taskId;
            const modal = document.getElementById('missionModal');
            const deleteBtn = document.getElementById('btnDeleteMission');
            const catSelect = document.getElementById('missionCat');
            catSelect.innerHTML = CATEGORIES_MAP.map(c => `<option value="${c.id}">${c.label}</option>`).join('');

            if (mode === 'create') {
                document.getElementById('modalTitle').innerText = 'Nova Missão';
                document.getElementById('missionTitle').value = '';
                document.getElementById('missionTime').value = getSuggestedTime(selectedDayIndex);
                document.getElementById('missionXP').value = 50;
                deleteBtn.classList.add('hidden');
                document.querySelectorAll('.day-checkbox').forEach((cb, idx) => { cb.checked = idx === selectedDayIndex; });
            } else if (mode === 'edit' && taskId) {
                document.getElementById('modalTitle').innerText = 'Editar Missão';
                let task = customTasksData[taskId];
                let isStatic = false;
                if (!task) {
                   const dayRoutine = WEEKLY_ROUTINE[selectedDayIndex] || [];
                   task = dayRoutine.find(t => t.id === taskId);
                   isStatic = true;
                }
                if (task) {
                   document.getElementById('missionTitle').value = task.title;
                   document.getElementById('missionTime').value = task.time;
                   document.getElementById('missionCat').value = task.cat;
                   document.getElementById('missionXP').value = task.xpBase || 50;
                   document.querySelectorAll('.day-checkbox').forEach((cb, idx) => {
                        if (task.recurrenceDays) cb.checked = task.recurrenceDays.includes(idx);
                        else cb.checked = idx === selectedDayIndex; 
                   });
                   if (!isStatic) deleteBtn.classList.remove('hidden');
                   else deleteBtn.classList.add('hidden');
                }
            }
            modal.classList.remove('hidden'); modal.classList.add('flex');
        };

        window.closeMissionModal = () => {
            const modal = document.getElementById('missionModal');
            modal.classList.add('hidden'); modal.classList.remove('flex');
            currentEditingTaskId = null;
        }

        document.addEventListener('DOMContentLoaded', () => {
            const titleInput = document.getElementById('missionTitle');
            if(titleInput) {
                titleInput.addEventListener('input', (e) => {
                    const suggestion = suggestCategory(e.target.value);
                    document.getElementById('missionCat').value = suggestion;
                });
             }
        });

        window.saveMission = async () => {
            if (!db || !currentUserId) return;
            const title = document.getElementById('missionTitle').value;
            const time = document.getElementById('missionTime').value;
            const cat = document.getElementById('missionCat').value;
            const xpBase = parseInt(document.getElementById('missionXP').value);
            const recurrenceDays = [];
            document.querySelectorAll('.day-checkbox:checked').forEach(cb => recurrenceDays.push(parseInt(cb.value)));

            if(!title) return alert("Digite um título!");
            if(recurrenceDays.length === 0) return alert("Selecione pelo menos um dia!");

            const catInfo = CATEGORIES_MAP.find(c => c.id === cat);
            const wheelKey = catInfo ? catInfo.wheelKey : 'carreira';
            const taskData = { title, time, cat, xpBase, recurrenceDays, wheelKey, updatedAt: new Date().toISOString() };
            const docId = currentEditingTaskId && customTasksData[currentEditingTaskId] ? currentEditingTaskId : 'custom_' + Date.now();
            taskData.id = docId;

            await setDoc(doc(db, `artifacts/${appId}/users/${currentUserId}/custom_tasks`, docId), taskData, { merge: true });
            closeMissionModal();
        };

        window.deleteMission = async () => {
            if (!db || !currentUserId || !currentEditingTaskId) return;
            if (confirm("Tem certeza que deseja excluir esta missão?")) {
                await deleteDoc(doc(db, `artifacts/${appId}/users/${currentUserId}/custom_tasks`, currentEditingTaskId));
                closeMissionModal();
            }
        }

        // --- STREAK & LOGICA 21 DIAS (CORRIGIDO) ---
        async function updateChallengeStats(challengeTag, isChecking, taskDate) {
            if (!db || !currentUserId) return;
            const challengeDef = CHALLENGES.find(c => c.tag === challengeTag);
            if (!challengeDef) return;
            const challengeId = challengeDef.id;

            let stats = challengesStatus[challengeId] || { Contagem_Conclusoes_Total: 0, Status_21D_Concluido: false };

            if (isChecking) {
               // Se já concluiu, não faz nada (trava no 21)
               if (stats.Status_21D_Concluido) return;

               stats.Contagem_Conclusoes_Total = (stats.Contagem_Conclusoes_Total || 0) + 1;
               
               if (stats.Contagem_Conclusoes_Total >= 21) {
                   stats.Status_21D_Concluido = true;
                   stats.Contagem_Conclusoes_Total = 21; // Trava no 21
                   showToast(`Parabéns! Desafio ${challengeDef.name} CONCLUÍDO! 🏆`);
               }
            } else {
               // Se desmarcar, diminui a contagem, a menos que já tenha concluído (opcional, aqui vou deixar diminuir se o usuário quiser 'reabrir' o desafio)
               stats.Contagem_Conclusoes_Total = Math.max(0, (stats.Contagem_Conclusoes_Total || 0) - 1);
               if (stats.Contagem_Conclusoes_Total < 21) stats.Status_21D_Concluido = false;
            }
            
            challengesStatus[challengeId] = stats;
            renderAll();
            await setDoc(doc(db, `artifacts/${appId}/users/${currentUserId}/life_wheel`, 'challenges_status'), { [challengeId]: stats }, { merge: true });
        }

        // --- ACTIONS ---
        window.saveWheelScore = async (area, value) => {
            if (!db) return;
            if(!wheelData.scores) wheelData.scores = {};
            wheelData.scores[area] = parseInt(value);
            await setDoc(doc(db, `artifacts/${appId}/users/${currentUserId}/life_wheel`, 'weekly_data'), { scores: wheelData.scores }, { merge: true });
        };
        window.toggleFocusCategory = async (catId) => {
            if (!db) return;
            let currentFocus = wheelData.focusCategories || [];
            if (currentFocus.includes(catId)) currentFocus = currentFocus.filter(c => c !== catId);
            else if (currentFocus.length < 3) currentFocus.push(catId);
            else return alert("Máximo de 3 áreas de foco!");
            wheelData.focusCategories = currentFocus;
            renderAll();
            await setDoc(doc(db, `artifacts/${appId}/users/${currentUserId}/life_wheel`, 'weekly_data'), { focusCategories: currentFocus }, { merge: true });
        };
        window.saveFocus = async (text) => await setDoc(doc(db, `artifacts/${appId}/users/${currentUserId}/life_wheel`, 'weekly_data'), { focus: text }, { merge: true });
        window.saveReview = async (field, text) => {
            const review = { ...(wheelData.review || {}), [field]: text };
            await setDoc(doc(db, `artifacts/${appId}/users/${currentUserId}/life_wheel`, 'weekly_data'), { review }, { merge: true });
        };
        window.toggleHabit = async (date, habitId) => {
            const currentStatus = dailyData[date]?.[habitId] || false;
            if(!dailyData[date]) dailyData[date] = {};
            dailyData[date][habitId] = !currentStatus;
            renderAll(); 
            if (!currentStatus) showXPToast(50, false, event.target); 
            if (db && currentUserId) await setDoc(doc(db, `artifacts/${appId}/users/${currentUserId}/daily_data`, date), { [habitId]: !currentStatus }, { merge: true });
        };
        window.toggleTask = async (date, taskId, xpBase, category, challengeTag) => {
            const currentStatus = dailyData[date]?.[taskId] || false;
            const newStatus = !currentStatus;
            if(!dailyData[date]) dailyData[date] = {};
            dailyData[date][taskId] = newStatus;
            
            if (challengeTag) await updateChallengeStats(challengeTag, newStatus, date);
            
            renderAll(); 
            if (newStatus) {
                const isFocus = (wheelData.focusCategories || []).includes(category);
                const finalXP = isFocus ? xpBase * 2 : xpBase;
                const checkbox = document.getElementById(`chk_${taskId}`);
                if(checkbox) showXPToast(finalXP, isFocus, checkbox);
            }
            if (db && currentUserId) await setDoc(doc(db, `artifacts/${appId}/users/${currentUserId}/daily_data`, date), { [taskId]: newStatus }, { merge: true });
        };
        window.selectDay = (dayIndex) => { selectedDayIndex = dayIndex; renderAgenda(); };
        window.navigate = (screenId) => {
            document.querySelectorAll('.screen-section').forEach(el => el.classList.remove('active'));
            document.querySelectorAll('.nav-item').forEach(el => el.classList.remove('active'));
            document.getElementById(screenId).classList.add('active');
            const navBtn = document.querySelector(`[onclick="navigate('${screenId}')"]`);
            if(navBtn) navBtn.classList.add('active');
            window.scrollTo(0,0);
            if(screenId === 'screenEvolution') renderEvolution();
        };

        // --- CALCS & HELPERS ---
        function calculateTagStreak(tag) {
            // Mantido para badges de streak simples (se houver), mas a lógica principal de 21 dias agora é fixa no contador
            let streak = 0;
            for (let i = 0; i < 30; i++) {
                const dateStr = window.getDateStringAgo(i);
                const d = new Date(); d.setDate(d.getDate() - i);
                const dayIndex = d.getDay() === 0 ? 6 : d.getDay() - 1;
                const tasks = (WEEKLY_ROUTINE[dayIndex] || []).filter(t => t.challengeTag === tag);
                if (tasks.length === 0) continue;
                const done = tasks.some(t => dailyData[dateStr]?.[t.id]);
                if (done) streak++; else { if (i === 0) continue; break; }
            }
            return streak;
        }

        function calculateXPStats() {
            let totalXP = 0;
            const focusCats = wheelData.focusCategories || [];
            let weeklyHistory = [0, 0, 0, 0]; 
            for (let i = 0; i < 30; i++) {
                const date = window.getDateStringAgo(i);
                if(!dailyData[date]) continue;
                const d = new Date(); d.setDate(d.getDate() - i);
                const dayIdx = d.getDay() === 0 ? 6 : d.getDay() - 1;
                const weekIdx = Math.floor(i / 7); 
                let dayXP = 0;
                ['gratidao', 'exercicio', 'meditacao'].forEach(h => { if(dailyData[date][h]) dayXP += 50; });
                 
                // Get merged tasks for history calc
                const staticTasks = WEEKLY_ROUTINE[dayIdx] || [];
                const customTasks = Object.values(customTasksData).filter(t => t.recurrenceDays && t.recurrenceDays.includes(dayIdx));
                const allTasks = [...staticTasks, ...customTasks];

                allTasks.forEach(t => {
                   if(dailyData[date][t.id]) {
                       const isFocus = focusCats.includes(t.cat);
                       dayXP += isFocus ? (t.xpBase * 2) : t.xpBase;
                   }
                });
                if(weekIdx < 4) weeklyHistory[3 - weekIdx] += dayXP; 
                totalXP += dayXP;
            }
            if (wheelData.scores && Object.keys(wheelData.scores).length >= 4) totalXP += 300;
            if (wheelData.review && wheelData.review.wins) totalXP += 500;
            
            // Add XP dos desafios concluídos
            CHALLENGES.forEach(ch => { 
                const stats = challengesStatus[ch.id];
                if(stats && stats.Status_21D_Concluido) totalXP += 1500; 
            });
            
            return { total: totalXP, history: weeklyHistory };
        }

        function getDailyHeatmapData() {
            const map = [];
            for(let i=0; i<7; i++) {
                const dateStr = window.getDateStringForDay(i);
                const dayTasks = WEEKLY_ROUTINE[i] || []; // Only static for heatmap simplicity
                if(dayTasks.length === 0) { map.push({ level: 0, label: ['S','T','Q','Q','S','S','D'][i] }); continue; }
                let done = 0;
                dayTasks.forEach(t => { if(dailyData[dateStr]?.[t.id]) done++; });
                const pct = done / dayTasks.length;
                let level = 0;
                if(pct > 0) level = 1; if(pct > 0.4) level = 2; if(pct > 0.7) level = 3; if(pct >= 1) level = 4;
                map.push({ level, label: ['S','T','Q','Q','S','S','D'][i] });
            }
            return map;
        }

        function getLevelInfo(xp) {
            for (let i = LEVELS.length - 1; i >= 0; i--) if (xp >= LEVELS[i].threshold) return LEVELS[i];
            return LEVELS[0];
        }

        function showXPToast(amount, isBonus, element) {
            if(!element) return;
            const toast = document.createElement('div'); toast.className = 'xp-float';
            toast.innerText = `+${amount} XP${isBonus ? ' 🔥' : '!'}`;
            const rect = element.getBoundingClientRect();
            toast.style.left = `${rect.left + window.scrollX + 20}px`;
            toast.style.top = `${rect.top + window.scrollY - 20}px`;
            document.body.appendChild(toast); setTimeout(() => toast.remove(), 1200);
        }

        function showToast(msg) {
            const toast = document.createElement('div');
            toast.className = 'fixed top-6 left-1/2 transform -translate-x-1/2 bg-gray-900 text-will-yellow px-6 py-3 rounded-full shadow-2xl z-[100] font-bold text-sm animate-[fadeIn_0.3s] flex items-center gap-2 border border-yellow-500';
            toast.innerHTML = msg;
            document.body.appendChild(toast);
            setTimeout(() => { toast.style.opacity = '0'; setTimeout(() => toast.remove(), 300); }, 3000);
        }
        
        window.showTargetInfo = (name, valReal, valIdeal, color) => {
            const tooltip = document.getElementById('targetTooltip');
            if(tooltip) {
                const diff = valReal - valIdeal;
                let status = diff > 5 ? '<span class="text-green-600 font-bold">Superou! 🔥</span>' : (diff < -5 ? '<span class="text-red-500 font-bold">Déficit ⚠️</span>' : '<span class="text-gray-500 font-bold">Equilibrado✨</span>');
                tooltip.innerHTML = `<div class="flex flex-col items-center justify-center gap-1 animate-[fadeIn_0.2s]"><div class="flex items-center gap-2 mb-1"><div class="w-3 h-3 rounded-full" style="background-color: ${color}"></div><span class="font-bold text-gray-800 capitalize text-sm">${name}</span></div><div class="grid grid-cols-2 gap-x-6 text-xs w-full px-4"><div class="text-right border-r border-gray-200 pr-3"><div class="text-gray-400 text-[9px] uppercase">Real</div><div class="font-bold text-lg" style="color: ${color}">${Math.round(valReal)}%</div></div><div class="text-left pl-1"><div class="text-gray-400 text-[9px] uppercase">Ideal</div><div class="font-bold text-lg text-gray-400">${Math.round(valIdeal)}%</div></div></div><div class="mt-1 text-xs">${status}</div></div>`;
            }
        };

        // --- EVOLUTION LOGIC ---
        window.setEvolutionPeriod = (days) => {
            evolutionPeriod = days;
            document.querySelectorAll('.filter-btn').forEach(b => {
                b.classList.remove('active', 'inactive');
                if(parseInt(b.dataset.days) === days) b.classList.add('active'); else b.classList.add('inactive');
             });
            renderEvolution();
        };

        function getPeriodData(days) {
            let totalMissions = 0; let totalXP = 0; let dailyConsistency = []; let categoryCompletion = {};
            CATEGORIES_MAP.forEach(c => categoryCompletion[c.wheelKey] = {total: 0, done: 0});
            for(let i = days-1; i >= 0; i--) {
                const date = window.getDateStringAgo(i);
                const d = new Date(); d.setDate(d.getDate() - i);
                let label = '';
                if(days === 7) label = ['Dom','Seg','Ter','Qua','Qui','Sex','Sáb'][d.getDay()]; else label = d.getDate(); 

                const dayIdx = d.getDay() === 0 ? 6 : d.getDay() - 1;
                const staticTasks = WEEKLY_ROUTINE[dayIdx] || [];
                const customTasks = Object.values(customTasksData).filter(t => t.recurrenceDays && t.recurrenceDays.includes(dayIdx));
                const tasks = [...staticTasks, ...customTasks];

                let dayTotal = 0; let dayDone = 0;
                tasks.forEach(t => {
                   dayTotal++;
                   const catInfo = CATEGORIES_MAP.find(c => c.id === t.cat);
                   const key = catInfo ? catInfo.wheelKey : 'admin';
                   if(!categoryCompletion[key]) categoryCompletion[key] = {total:0, done:0};
                   categoryCompletion[key].total++;
                   if(dailyData[date]?.[t.id]) {
                       dayDone++; categoryCompletion[key].done++; totalXP += (t.xpBase || 50);
                   }
                });
                 
                let pct = 0;
                if(dayTotal > 0) pct = Math.round((dayDone/dayTotal)*100);
                dailyConsistency.push({ label: label, val: pct, date: date });
                totalMissions += dayDone;
             }
            return { totalMissions, totalXP, dailyConsistency, categoryCompletion };
        }

        function calculateInsights(data, days) {
            let bestCat = {name: '-', val: -1}; let worstCat = {name: '-', val: 999};
            Object.entries(data.categoryCompletion).forEach(([key, val]) => {
                if(val.total > 0) {
                   const pct = (val.done / val.total) * 100;
                   if(pct > bestCat.val) bestCat = {name: key, val: pct};
                   if(pct < worstCat.val) worstCat = {name: key, val: pct};
                 }
             });
            return { bestCat, worstCat };
        }

        function getSmoothPath(points, graphW, graphH, padL, padT) {
            if (points.length === 0) return "";
            if (points.length === 1) return "";
            const coords = points.map((p, i) => ({ x: padL + (i / (points.length - 1)) * graphW, y: padT + graphH - (p.val / 100) * graphH }));
            let d = `M ${coords[0].x} ${coords[0].y}`;
            for (let i = 0; i < coords.length - 1; i++) {
                const p0 = coords[i]; const p1 = coords[i + 1];
                const cp1x = p0.x + (p1.x - p0.x) * 0.5; const cp1y = p0.y;
                const cp2x = p0.x + (p1.x - p0.x) * 0.5; const cp2y = p1.y;
                 d += ` C ${cp1x} ${cp1y}, ${cp2x} ${cp2y}, ${p1.x} ${p1.y}`;
            }
            return d;
        }

        // --- RENDERIZADORES ---
        function renderAll() {
            if (!isDomReady) return;
            const stats = calculateXPStats();
            const levelInfo = getLevelInfo(stats.total);
            renderDashboard(stats.total, levelInfo, stats.history);
            renderSetup();
            renderAgenda();
            renderReview(stats.total);
            if(document.getElementById('screenEvolution').classList.contains('active')) renderEvolution();
        }

        function renderDashboard(xp, levelInfo, xpHistory) {
            if(els.levelName) {
                els.levelName.innerText = levelInfo.name;
                els.levelName.className = `font-bold text-sm uppercase tracking-wider mb-1 ${levelInfo.color}`;
            }
            if(els.xpDisplay) els.xpDisplay.innerText = `${xp} XP`;
            const today = new Date();
            const options = { weekday: 'long', day: 'numeric', month: 'long' };
            if(els.currentDateDisplay) els.currentDateDisplay.innerText = today.toLocaleDateString('pt-BR', options);
            const scores = Object.values(wheelData.scores || {});
            const avg = scores.length ? (scores.reduce((a,b)=>a+b,0)/scores.length).toFixed(1) : '0.0';
            if(els.dashWheelAvg) els.dashWheelAvg.innerText = avg;
            
            if(els.heatmapContainer) {
                const mapData = getDailyHeatmapData();
                els.heatmapContainer.innerHTML = mapData.map(d => `
                   <div class="flex flex-col items-center gap-1 w-full">
                       <div class="heatmap-box lvl-${d.level}"></div>
                       <span class="text-[9px] font-bold text-gray-400">${d.label}</span>
                   </div>`).join('');
            }
            if(els.challengesWidget) {
                els.challengesWidget.innerHTML = CHALLENGES.map(ch => {
                   const chData = challengesStatus[ch.id] || { Contagem_Conclusoes_Total: 0, Status_21D_Concluido: false };
                   const percent = Math.min(100, (chData.Contagem_Conclusoes_Total / 21) * 100);

                   if (chData.Status_21D_Concluido) {
                       return `
                       <div class="bg-green-50 p-3 rounded-2xl border border-green-200 mb-2 flex items-center justify-between">
                           <div class="flex items-center">
                               <div class="text-2xl mr-3">🏆</div>
                               <div><div class="text-xs font-bold text-green-900 uppercase">${ch.name}</div><div class="text-[10px] text-green-600 font-bold">DESAFIO CONCLUÍDO!</div></div>
                           </div>
                           <div class="text-right"><div class="text-lg font-bold text-green-600 leading-none">21/21</div></div>
                       </div>`;
                   } else {
                       return `
                       <div class="bg-gray-50 p-3 rounded-2xl border border-gray-100 mb-2 flex items-center justify-between">
                           <div class="flex items-center"><div class="text-2xl mr-3">${ch.icon}</div><div><div class="text-xs font-bold text-gray-800 uppercase">${ch.name}</div><div class="text-[10px] text-gray-500">${ch.desc}</div></div></div>
                           <div class="w-24 text-right"><div class="text-xs font-bold mb-1 text-gray-900">${chData.Contagem_Conclusoes_Total}/21</div><div class="progress-bar"><div class="progress-fill bg-will-yellow" style="width: ${percent}%"></div></div></div>
                       </div>`;
                   }
                }).join('');
            }
        }

        function renderAgenda() {
            const days = ['Seg', 'Ter', 'Qua', 'Qui', 'Sex', 'Sáb', 'Dom'];
            let tabsHtml = '';
            days.forEach((d, idx) => {
                const isActive = idx === selectedDayIndex ? 'active' : '';
                const dateStr = window.getDateStringForDay(idx);
                const [year, month, day] = dateStr.split('-');
                tabsHtml += `<div class="day-tab ${isActive}" onclick="selectDay(${idx})"><span>${d}</span><span class="date">${day}/${month}</span></div>`;
            });
            if(els.dayTabsContainer) els.dayTabsContainer.innerHTML = tabsHtml;

            const staticTasks = WEEKLY_ROUTINE[selectedDayIndex] || [];
            const customTasks = Object.values(customTasksData).filter(t => t.recurrenceDays && t.recurrenceDays.includes(selectedDayIndex));
            const allTasks = [...staticTasks, ...customTasks];
            
            const getStartHour = (timeStr) => {
                const clean = timeStr.replace('~', '').split('-')[0].toLowerCase().replace('h','.').replace(':','.');
                return parseFloat(clean) || 0;
            };
            allTasks.sort((a,b) => getStartHour(a.time) - getStartHour(b.time));

            const dateStr = window.getDateStringForDay(selectedDayIndex);
            let tasksHtml = '';
            
            if(allTasks.length === 0) tasksHtml = `<div class="text-center text-gray-400 py-8">Dia livre! Aproveite. 😎</div>`;
            else {
                allTasks.forEach((task) => {
                   const style = CATEGORY_STYLES[task.cat] || "bg-white border-gray-200 text-gray-700 border-l-4";
                   const isDone = dailyData[dateStr]?.[task.id];
                   const isFocus = (wheelData.focusCategories || []).includes(task.cat);
                   
                   let badgeHtml = '';
                   if (task.challengeTag) badgeHtml = `<span class="inline-flex items-center gap-1 ml-2 bg-purple-100 text-purple-700 px-2 py-0.5 rounded-full text-[10px] font-bold border border-purple-200">21D</span>`;

                   tasksHtml += `
                   <div class="relative pl-2 group">
                       <div class="p-4 rounded-3xl ${style} shadow-sm mb-4 flex justify-between items-center transition transform active:scale-95 relative">
                           <div onclick="openMissionModal('edit', '${task.id}')" class="absolute top-2 right-2 text-gray-400 hover:text-gray-800 p-1 cursor-pointer z-10">
                               <i data-lucide="pencil" class="w-3 h-3"></i>
                           </div>
                           <div>
                               <span class="block text-xs font-bold opacity-70 mb-1 tracking-wide uppercase flex items-center">
                                   ${task.time} ${isFocus ? '<span class="ml-1 text-will-yellow">⚡</span>' : ''}
                                   ${badgeHtml}
                               </span>
                               <span class="font-bold text-lg leading-tight block ${isDone ? 'line-through opacity-50' : ''}">${task.title}</span>
                               ${task.sub ? `<p class="text-sm opacity-90 mt-1 font-medium">• ${task.sub}</p>` : ''}
                           </div>
                           <div id="chk_${task.id}" onclick="toggleTask('${dateStr}', '${task.id}', ${task.xpBase || 50}, '${task.cat}', '${task.challengeTag || ''}')" class="gamified-checkbox ${isDone ? 'checked' : ''}">
                               ${isDone ? '<i data-lucide="check" class="w-4 h-4 text-black"></i>' : ''}
                           </div>
                       </div>
                   </div>`;
                });
            }
            if(els.agendaListContainer) els.agendaListContainer.innerHTML = tasksHtml;
            lucide.createIcons();
            
            // Renderiza Hábito Grid
            const habits = [{id: 'gratidao', label: 'Gratidão'}, {id: 'exercicio', label: 'Exercício'}, {id: 'meditacao', label: 'Meditação'}];
            let habitsHtml = `<div class="font-bold text-xs text-center text-gray-400 self-end pb-2">Hábito</div>`;
            days.forEach(d => habitsHtml += `<div class="font-bold text-xs text-center text-gray-800 pb-2">${d}</div>`);
            habits.forEach(h => {
                habitsHtml += `<div class="text-xs font-bold text-right pr-3 text-gray-500 flex justify-end items-center">${h.label}</div>`;
                days.forEach((d, idx) => {
                   const date = window.getDateStringForDay(idx);
                   const isDone = dailyData[date]?.[h.id];
                   habitsHtml += `<div class="habit-btn ${isDone ? 'done' : 'pending'}" onclick="toggleHabit('${date}', '${h.id}')">${isDone ? '✓' : ''}</div>`;
                });
            });
            if(els.agendaHabits) els.agendaHabits.innerHTML = habitsHtml;
        }

        function renderEvolution() {
            const data = getPeriodData(evolutionPeriod);
            const insights = calculateInsights(data, evolutionPeriod);
            if(els.evoMissions) els.evoMissions.innerText = data.totalMissions;
            if(els.evoXP) els.evoXP.innerText = data.totalXP;
            
            if(els.lineChart) {
                const dataset = data.dailyConsistency; 
                const count = dataset.length;
                const w = 300, h = 150;
                const padL = 30, padR = 20, padT = 20, padB = 30; 
                const graphW = w - padL - padR; const graphH = h - padT - padB;
                const getX = (i) => padL + (i / (count - 1)) * graphW; const getY = (val) => padT + graphH - (val / 100) * graphH;

                let svgContent = '';
                [0, 50, 100].forEach(val => { const y = getY(val); svgContent += `<line x1="${padL}" y1="${y}" x2="${w - padR}" y2="${y}" stroke="#E5E7EB" stroke-width="1" /><text x="${padL - 5}" y="${y + 3}" text-anchor="end" font-size="10" fill="#9CA3AF">${val}%</text>`; });
                const yTarget = getY(80); svgContent += `<line x1="${padL}" y1="${yTarget}" x2="${w - padR}" y2="${yTarget}" stroke="#86EFAC" stroke-width="1.5" stroke-dasharray="4 4" />`;
                if (count > 1) { const d = getSmoothPath(dataset, graphW, graphH, padL, padT); svgContent += `<path d="${d}" fill="none" stroke="#374151" stroke-width="3" stroke-linecap="round" stroke-linejoin="round" />`; }
                dataset.forEach((pt, i) => { const cx = getX(i); const cy = getY(pt.val); svgContent += `<circle cx="${cx}" cy="${cy}" r="4" fill="#FFEA00" stroke="#374151" stroke-width="1.5" />`;
                if(count <= 7 || i % 5 === 0) svgContent += `<text x="${cx}" y="${h - 10}" text-anchor="middle" font-size="10" font-weight="bold" fill="#6B7280">${pt.label}</text>`;
                });
                els.lineChart.setAttribute('viewBox', `0 0 ${w} ${h}`); els.lineChart.innerHTML = svgContent;
            }
            
            if(els.radarChart) {
                const keys = ['saude','carreira','financas','lazer','espiritualidade','intelecto','emocional','relacionamentos'];
                const maxR = 40; const center = 50;
                const pointsReal = []; const pointsIdeal = []; const dotElements = [];

                keys.forEach((key, i) => {
                   const angle = (Math.PI * 2 * i / 8) - (Math.PI / 2); 
                   const stats = data.categoryCompletion[key] || {total:1, done:0};
                   let pctReal = stats.total ? (stats.done / stats.total) * 100 : 0;
                   let scoreIdeal = wheelData.scores?.[key] || 0; let pctIdeal = scoreIdeal * 10; 

                   const rReal = (pctReal / 100) * maxR; const xReal = center + rReal * Math.cos(angle); const yReal = center + rReal * Math.sin(angle); pointsReal.push(`${xReal},${yReal}`);
                   const rIdeal = (pctIdeal / 100) * maxR; const xIdeal = center + rIdeal * Math.cos(angle); const yIdeal = center + rIdeal * Math.sin(angle); pointsIdeal.push(`${xIdeal},${yIdeal}`);

                   const color = WHEEL_COLORS[key] || '#9CA3AF';
                   dotElements.push(`<circle cx="${xReal}" cy="${yReal}" r="3.5" fill="${color}" stroke="white" stroke-width="1.5" class="target-dot" onclick="showTargetInfo('${key}', ${pctReal}, ${pctIdeal}, '${color}')" />`);
                });

                let svgContent = `
                   <circle cx="${center}" cy="${center}" r="${maxR}" fill="#F9FAFB" stroke="#E5E7EB" stroke-width="1" />
                   <circle cx="${center}" cy="${center}" r="${maxR * 0.75}" fill="none" stroke="#E5E7EB" stroke-width="1" />
                   <circle cx="${center}" cy="${center}" r="${maxR * 0.5}" fill="none" stroke="#E5E7EB" stroke-width="1" />
                   <circle cx="${center}" cy="${center}" r="${maxR * 0.25}" fill="none" stroke="#E5E7EB" stroke-width="1" />
                   <line x1="${center}" y1="10" x2="${center}" y2="90" stroke="#E5E7EB" stroke-width="1"/>
                   <line x1="10" y1="${center}" x2="90" y2="${center}" stroke="#E5E7EB" stroke-width="1"/>
                   <line x1="22" y1="22" x2="78" y2="78" stroke="#E5E7EB" stroke-width="1"/>
                   <line x1="78" y1="22" x2="22" y2="78" stroke="#E5E7EB" stroke-width="1"/>
                   <polygon points="${pointsIdeal.join(' ')}" fill="rgba(156, 163, 175, 0.1)" stroke="#9CA3AF" stroke-width="1.5" stroke-dasharray="2 2" />
                   <polygon points="${pointsReal.join(' ')}" fill="rgba(255, 234, 0, 0.3)" stroke="#EAB308" stroke-width="2" />
                   ${dotElements.join('')}`;
                els.radarChart.innerHTML = svgContent;
            }
            if(els.targetLegend) els.targetLegend.innerHTML = `<div class="col-span-2 flex justify-center gap-4 mb-2"><div class="flex items-center gap-1"><div class="w-3 h-3 bg-will-yellow opacity-50 border border-yellow-600"></div><span class="text-[10px] font-bold text-gray-600 uppercase">Execução Real</span></div><div class="flex items-center gap-1"><div class="w-3 h-3 border border-gray-400 border-dashed"></div><span class="text-[10px] font-bold text-gray-400 uppercase">Nota Ideal</span></div></div>`;
            if(els.insightHigh) els.insightHigh.innerHTML = `<span class="capitalize font-bold text-green-700">${insights.bestCat.name}</span><div class="text-2xl font-bold">${Math.round(insights.bestCat.val)}%</div>`;
            if(els.insightLow) els.insightLow.innerHTML = `<span class="capitalize font-bold text-red-700">${insights.worstCat.name}</span><div class="text-2xl font-bold">${Math.round(insights.worstCat.val)}%</div>`;
            if(els.insightSuggestion) els.insightSuggestion.innerText = `Sua consistência em ${insights.worstCat.name} (${Math.round(insights.worstCat.val)}%) está abaixo da média. Tente reduzir a meta diária para aumentar a adesão.`;
        }

        function renderSetup() {
            const areas = ['saude', 'carreira', 'financas', 'relacionamentos', 'lazer', 'espiritualidade', 'intelecto', 'emocional'];
            if(els.wheelContainer && els.wheelContainer.innerHTML === '') {
                els.wheelContainer.innerHTML = areas.map(area => `<div class="flex flex-col items-center"><span class="text-[10px] font-bold text-gray-500 mb-2 uppercase tracking-wide">${area.substring(0,6)}</span><input type="number" min="1" max="10" class="wheel-score-input" id="input_${area}" onchange="saveWheelScore('${area}', this.value)"></div>`).join('');
            }
            areas.forEach(area => { const inp = document.getElementById(`input_${area}`); if(inp && wheelData.scores) inp.value = wheelData.scores[area] || ''; });
            const focusCats = wheelData.focusCategories || [];
            if(els.focusSelector) {
                els.focusSelector.innerHTML = CATEGORIES_MAP.map(cat => {
                   const isSelected = focusCats.includes(cat.id);
                   return `<div onclick="toggleFocusCategory('${cat.id}')" class="px-3 py-2 rounded-full text-xs font-bold cursor-pointer border transition ${isSelected ? 'bg-will-yellow text-black border-black' : 'bg-white text-gray-500 border-gray-200'}">${cat.label}</div>`
                }).join('');
            }
            if(els.focusInput) els.focusInput.value = wheelData.focus || '';
        }

        function renderReview(xp) {
            if(els.reviewWins) els.reviewWins.value = wheelData.review?.wins || '';
            if(els.reviewLearn) els.reviewLearn.value = wheelData.review?.learn || '';
            if(els.badgeContainer) {
                els.badgeContainer.innerHTML = BADGES.map(badge => {
                   let unlocked = false;
                   if (badge.type === 'challenge' && badge.challengeId) {
                        unlocked = challengesStatus[CHALLENGES.find(c=>c.id===badge.challengeId)?.id]?.Status_21D_Concluido;
                   } else if(badge.type === 'streak') { 
                       const streak = calculateTagStreak(badge.tag); unlocked = streak >= badge.target; 
                   } else if (badge.type === 'count_weekly') {
                       let count = 0;
                       for(let i=0; i<7; i++) {
                           const date = window.getDateStringForDay(i); const dayTasks = WEEKLY_ROUTINE[i] || [];
                           const task = dayTasks.find(t => t.challengeTag === badge.tag);
                           if(task && dailyData[date] && dailyData[date][task.id]) count++;
                       }
                       unlocked = count >= badge.target;
                   } 
                   return `<div class="badge-card p-3 rounded-2xl flex flex-col items-center text-center ${unlocked ? 'unlocked' : ''}">${unlocked ? '<div class="badge-ribbon">GANHOU!</div>' : ''}<div class="text-2xl mb-1">${badge.icon}</div><div class="text-xs font-bold text-gray-800 leading-tight">${badge.name}</div><div class="text-[10px] text-gray-500 mt-1">${unlocked ? '+'+badge.xpBonus+' XP' : 'Bloqueado'}</div></div>`;
                }).join('');
            }
        }

        // --- INTELIGÊNCIA ---
        window.triggerNewCycle = () => { pendingSuggestions = calculateScoreSuggestions(); if (pendingSuggestions.length > 0) showSuggestionModal(); else navigate('screenSetup'); };
        function calculateScoreSuggestions() {
            const suggestions = []; const categoryStats = {}; 
            for(let i=0; i<7; i++) {
                const date = window.getDateStringAgo(i); const d = new Date(); d.setDate(d.getDate() - i);
                const dayIdx = d.getDay() === 0 ? 6 : d.getDay() - 1;
                const tasks = WEEKLY_ROUTINE[dayIdx] || [];
                tasks.forEach(t => {
                   const catInfo = CATEGORIES_MAP.find(c => c.id === t.cat); const wheelKey = catInfo ? catInfo.wheelKey : 'admin';
                   if(!categoryStats[wheelKey]) categoryStats[wheelKey] = {total: 0, done: 0}; categoryStats[wheelKey].total++;
                   if(dailyData[date]?.[t.id]) categoryStats[wheelKey].done++;
                });
            }
            Object.keys(categoryStats).forEach(key => {
                const stats = categoryStats[key];
                if(stats.total > 0) {
                   const executionRate = (stats.done / stats.total) * 10; const oldScore = wheelData.scores?.[key] || 5;
                   const newScore = ((oldScore * 0.7) + (executionRate * 0.3)).toFixed(1);
                   if(Math.abs(newScore - oldScore) >= 0.3) suggestions.push({ area: key, oldVal: oldScore, newVal: newScore, performance: Math.round((stats.done/stats.total)*100) });
                 }
            });
            return suggestions;
        }

        function showSuggestionModal() {
            const modal = document.getElementById('suggestionModal'); const list = document.getElementById('suggestionList');
            list.innerHTML = pendingSuggestions.map(s => `<div class="bg-gray-50 p-3 rounded-xl mb-2 border border-gray-200"><div class="flex justify-between items-center mb-1"><span class="font-bold text-sm uppercase text-gray-700">${s.area}</span><span class="text-xs bg-green-100 text-green-800 px-2 py-1 rounded-full font-bold">${s.performance}% Execução</span></div><div class="flex items-center justify-between text-sm"><span class="text-gray-400">Nota Atual: <b>${s.oldVal}</b></span><i data-lucide="arrow-right" class="w-4 h-4 text-gray-400"></i><span class="text-will-yellow font-bold text-lg bg-gray-900 px-2 rounded">Sugestão: ${s.newVal}</span></div></div>`).join('');
            modal.classList.remove('hidden'); modal.classList.add('flex');
            lucide.createIcons();
        }

        window.acceptSuggestions = async () => {
            if(!db) return; const newScores = { ...(wheelData.scores || {}) };
            pendingSuggestions.forEach(s => { newScores[s.area] = Math.round(s.newVal); });
            await setDoc(doc(db, `artifacts/${appId}/users/${currentUserId}/life_wheel`, 'weekly_data'), { scores: newScores }, { merge: true });
            closeModal(); navigate('screenSetup');
        };

        window.closeModal = () => { document.getElementById('suggestionModal').classList.add('hidden'); document.getElementById('suggestionModal').classList.remove('flex'); };

        function tryBootstrap() {
            if (isAuthReady && isDomReady) {
                els = {
                   levelName: document.getElementById('levelName'),
                   xpDisplay: document.getElementById('xpDisplay'),
                   dashWheelAvg: document.getElementById('dashWheelAvg'),
                   currentDateDisplay: document.getElementById('currentDateDisplay'),
                   challengesWidget: document.getElementById('challengesWidget'),
                   heatmapContainer: document.getElementById('heatmapContainer'),
                   evoMissions: document.getElementById('evoMissions'),
                   evoXP: document.getElementById('evoXP'),
                   lineChart: document.getElementById('lineChart'),
                   radarChart: document.getElementById('radarChart'),
                   targetLegend: document.getElementById('targetLegend'),
                   insightHigh: document.getElementById('insightHigh'),
                   insightLow: document.getElementById('insightLow'),
                   insightSuggestion: document.getElementById('insightSuggestion'),
                   wheelContainer: document.getElementById('wheelContainer'),
                   focusSelector: document.getElementById('focusSelector'),
                   focusInput: document.getElementById('focusInput'),
                   agendaHabits: document.getElementById('agendaHabits'),
                   dayTabsContainer: document.getElementById('dayTabsContainer'),
                   agendaListContainer: document.getElementById('agendaListContainer'),
                   reviewWins: document.getElementById('reviewWins'),
                   reviewLearn: document.getElementById('reviewLearn'),
                   badgeContainer: document.getElementById('badgeContainer')
                };
                setupListeners();
                lucide.createIcons();
                window.navigate('screenDashboard');
            }
        }
        document.addEventListener('DOMContentLoaded', () => { isDomReady = true; tryBootstrap(); });
    </script>
</head>
<body class="pb-28"> 
    <!-- MODAL DE MISSÃO (CRUD) -->
    <div id="missionModal" class="fixed inset-0 hidden items-center justify-center p-6 z-[1000]">
        <div class="bg-white w-full max-w-sm rounded-3xl p-6 shadow-2xl animate-[slideUp_0.3s]">
            <div class="flex justify-between items-center mb-6">
                <h3 id="modalTitle" class="font-bold text-xl text-gray-900">Nova Missão</h3>
                <button onclick="closeMissionModal()" class="text-gray-400 hover:text-gray-600"><i data-lucide="x" class="w-6 h-6"></i></button>
            </div>
            <div class="space-y-4">
                <div>
                  <label class="block text-xs font-bold text-gray-500 mb-1 uppercase">O que fazer?</label>
                  <input type="text" id="missionTitle" class="w-full p-3 bg-gray-50 border border-gray-200 rounded-xl font-bold text-gray-800 focus:border-will-yellow outline-none" placeholder="Ex: Ler 10 páginas">
                </div>
                <div class="flex gap-3">
                  <div class="flex-1">
                      <label class="block text-xs font-bold text-gray-500 mb-1 uppercase">Horário</label>
                      <input type="text" id="missionTime" class="w-full p-3 bg-gray-50 border border-gray-200 rounded-xl font-medium text-gray-800 focus:border-will-yellow outline-none" placeholder="10h - 11h">
                  </div>
                  <div class="w-24">
                      <label class="block text-xs font-bold text-gray-500 mb-1 uppercase">XP</label>
                      <input type="number" id="missionXP" class="w-full p-3 bg-gray-50 border border-gray-200 rounded-xl font-medium text-center text-gray-800 focus:border-will-yellow outline-none" value="50">
                  </div>
                </div>
                <div>
                  <label class="block text-xs font-bold text-gray-500 mb-1 uppercase">Categoria (IA Sugere)</label>
                  <div class="relative">
                      <select id="missionCat" class="w-full p-3 bg-gray-50 border border-gray-200 rounded-xl font-medium text-gray-800 appearance-none focus:border-will-yellow outline-none"></select>
                      <i data-lucide="chevron-down" class="absolute right-3 top-3.5 w-4 h-4 text-gray-400 pointer-events-none"></i>
                  </div>
                </div>
                <div>
                  <label class="block text-xs font-bold text-gray-500 mb-2 uppercase">Recorrência</label>
                  <div class="flex justify-between gap-1">
                      <label class="cursor-pointer"><input type="checkbox" value="0" class="day-checkbox hidden peer"><div class="w-8 h-8 rounded-lg bg-gray-100 flex items-center justify-center text-xs font-bold text-gray-400 peer-checked:bg-will-yellow peer-checked:text-black transition">S</div></label>
                      <label class="cursor-pointer"><input type="checkbox" value="1" class="day-checkbox hidden peer"><div class="w-8 h-8 rounded-lg bg-gray-100 flex items-center justify-center text-xs font-bold text-gray-400 peer-checked:bg-will-yellow peer-checked:text-black transition">T</div></label>
                      <label class="cursor-pointer"><input type="checkbox" value="2" class="day-checkbox hidden peer"><div class="w-8 h-8 rounded-lg bg-gray-100 flex items-center justify-center text-xs font-bold text-gray-400 peer-checked:bg-will-yellow peer-checked:text-black transition">Q</div></label>
                      <label class="cursor-pointer"><input type="checkbox" value="3" class="day-checkbox hidden peer"><div class="w-8 h-8 rounded-lg bg-gray-100 flex items-center justify-center text-xs font-bold text-gray-400 peer-checked:bg-will-yellow peer-checked:text-black transition">Q</div></label>
                      <label class="cursor-pointer"><input type="checkbox" value="4" class="day-checkbox hidden peer"><div class="w-8 h-8 rounded-lg bg-gray-100 flex items-center justify-center text-xs font-bold text-gray-400 peer-checked:bg-will-yellow peer-checked:text-black transition">S</div></label>
                      <label class="cursor-pointer"><input type="checkbox" value="5" class="day-checkbox hidden peer"><div class="w-8 h-8 rounded-lg bg-gray-100 flex items-center justify-center text-xs font-bold text-gray-400 peer-checked:bg-will-yellow peer-checked:text-black transition">S</div></label>
                      <label class="cursor-pointer"><input type="checkbox" value="6" class="day-checkbox hidden peer"><div class="w-8 h-8 rounded-lg bg-gray-100 flex items-center justify-center text-xs font-bold text-gray-400 peer-checked:bg-will-yellow peer-checked:text-black transition">D</div></label>
                  </div>
                </div>
            </div>
            <div class="mt-6 flex gap-3">
                <button id="btnDeleteMission" onclick="deleteMission()" class="hidden px-4 py-3 bg-red-50 text-red-500 rounded-xl font-bold hover:bg-red-100 transition"><i data-lucide="trash-2" class="w-5 h-5"></i></button>
                <button onclick="saveMission()" class="flex-1 py-3 bg-will-yellow text-black rounded-xl font-bold shadow-lg hover:shadow-xl transition transform active:scale-95">Salvar Missão</button>
            </div>
        </div>
    </div>
    
    <!-- MODAL SUGESTÃO -->
    <div id="suggestionModal" class="fixed inset-0 hidden items-center justify-center p-6 z-[1000]">
        <div class="bg-white w-full max-w-sm rounded-3xl p-6 shadow-2xl animate-[slideUp_0.3s]">
            <div class="flex items-center mb-4 text-will-yellow"><i data-lucide="sparkles" class="w-6 h-6 mr-2 fill-black text-black"></i><h3 class="font-bold text-gray-900 text-lg">Inteligência da Rotina</h3></div>
            <p class="text-gray-500 text-sm mb-4">Com base no que você realizou essa semana, calculamos novos scores:</p>
            <div id="suggestionList" class="mb-6 max-h-60 overflow-y-auto"></div>
            <div class="flex gap-3"><button onclick="closeModal(); navigate('screenSetup')" class="flex-1 py-3 text-sm font-bold text-gray-400 border border-gray-200 rounded-xl">Ignorar</button><button onclick="acceptSuggestions()" class="flex-1 py-3 text-sm font-bold bg-will-yellow text-black rounded-xl shadow-lg">Aceitar & Ajustar</button></div>
        </div>
    </div>

    <!-- TELA 1: DASHBOARD -->
    <section id="screenDashboard" class="screen-section active max-w-md mx-auto p-6">
        <header class="flex justify-between items-start mb-6 pt-4">
            <div><p id="levelName" class="font-bold text-sm uppercase tracking-wider mb-1 text-gray-400">O Desligado</p><h1 class="text-3xl font-bold text-gray-900 leading-none mb-1">Olá, Camis! 🚀</h1><p id="currentDateDisplay" class="text-xs text-gray-500 font-medium capitalize">Carregando data...</p></div>
            <div class="bg-gray-900 text-yellow-300 px-4 py-2 rounded-full font-bold text-sm shadow-lg border border-yellow-500" id="xpDisplay">-- XP</div>
        </header>
        <div class="mb-6"><div class="flex justify-between items-end mb-2"><h4 class="text-xs font-bold text-gray-400 uppercase">Consistência Diária</h4></div><div id="heatmapContainer" class="flex gap-1 justify-between bg-white p-3 rounded-xl border border-gray-100 shadow-sm"></div></div>
        <div class="grid grid-cols-2 gap-4 mb-6"><div class="bg-white p-4 rounded-3xl shadow-sm border border-gray-100 flex flex-col items-center justify-center"><div class="text-3xl font-bold text-will-yellow mb-1" id="dashWheelAvg">--</div><div class="text-xs font-bold text-gray-400 uppercase">Roda da Vida</div></div><div class="bg-white p-4 rounded-3xl shadow-sm border border-gray-100 flex flex-col items-center justify-center text-center"><div class="text-xl mb-1">🔥</div><div class="text-xs font-bold text-gray-400 uppercase">Sequência</div><div class="text-[10px] text-gray-500">Mantenha o ritmo!</div></div></div>
        <div class="bg-white p-4 rounded-3xl shadow-md border border-gray-100 mb-6"><h3 class="font-bold text-gray-900 text-sm uppercase tracking-wide mb-3 flex items-center"><i data-lucide="target" class="w-4 h-4 mr-2 text-will-yellow fill-black"></i> Desafios Ativos (21 Dias)</h3><div id="challengesWidget"></div></div>
        <div class="mt-4"><button onclick="navigate('screenSetup')" class="btn-primary w-full py-4 text-lg shadow-xl">Ganhar XP Hoje</button></div>
    </section>

    <!-- TELA 2: EVOLUÇÃO -->
    <section id="screenEvolution" class="screen-section max-w-md mx-auto p-6">
        <header class="mb-6 pt-4"><h2 class="text-2xl font-bold text-gray-700 mb-1">Evolução & Análise 📈</h2><div class="flex gap-2 mt-4 bg-gray-100 p-1 rounded-full w-full"><button onclick="setEvolutionPeriod(7)" data-days="7" class="filter-btn active flex-1">7 Dias</button><button onclick="setEvolutionPeriod(30)" data-days="30" class="filter-btn inactive flex-1">30 Dias</button><button onclick="setEvolutionPeriod(90)" data-days="90" class="filter-btn inactive flex-1">3 Meses</button></div></header>
        <div class="grid grid-cols-2 gap-4 mb-8"><div class="bg-white p-4 rounded-3xl shadow-sm border border-gray-100"><p class="text-[10px] font-bold text-gray-400 uppercase tracking-wide">Missões Concluídas</p><p id="evoMissions" class="text-3xl font-bold text-gray-900 mt-1">--</p></div><div class="bg-white p-4 rounded-3xl shadow-sm border border-gray-100"><p class="text-[10px] font-bold text-gray-400 uppercase tracking-wide">XP Acumulado</p><p id="evoXP" class="text-3xl font-bold text-will-yellow mt-1">--</p></div></div>
        <div class="mb-8"><div class="flex justify-between items-end mb-3 px-2"><h3 class="text-xs font-bold text-gray-500 uppercase">Consistência Total</h3><span class="text-[10px] text-gray-400">Tendência Diária</span></div><div class="bg-white p-4 rounded-3xl shadow-sm border border-gray-100 h-40 flex items-center justify-center relative overflow-visible"><svg id="lineChart" viewBox="0 0 100 100" preserveAspectRatio="none" class="w-full h-full overflow-visible"></svg></div></div>
        <div class="mb-8"><div class="flex justify-between items-end mb-3 px-2"><h3 class="text-xs font-bold text-gray-500 uppercase">Equilíbrio do Alvo</h3><span class="text-[10px] text-gray-400">Toque no ponto</span></div><div id="targetTooltip" class="bg-white p-3 rounded-2xl border border-gray-200 shadow-md mb-4 text-center min-h-[60px] flex flex-col items-center justify-center"><span class="text-xs text-gray-400">Toque em uma bolinha no alvo para ver detalhes</span></div><div class="bg-white p-4 rounded-3xl shadow-sm border border-gray-100 flex flex-col items-center py-6"><svg id="radarChart" viewBox="0 0 100 100" class="w-64 h-64 overflow-visible mb-4"></svg><div id="targetLegend" class="grid grid-cols-2 gap-x-4 gap-y-2 w-full px-4"></div></div></div>
        <div class="space-y-4 mb-8"><div class="bg-gray-100 p-5 rounded-3xl"><h4 class="text-xs font-bold text-gray-500 uppercase mb-3 flex items-center"><i data-lucide="zap" class="w-3 h-3 mr-2"></i> Destaques do Período</h4><div class="grid grid-cols-2 gap-4"><div class="bg-white p-3 rounded-2xl border border-gray-200"><p class="text-[10px] text-gray-400 uppercase">Maior Foco</p><div id="insightHigh" class="mt-1">--</div></div><div class="bg-white p-3 rounded-2xl border border-gray-200"><p class="text-[10px] text-gray-400 uppercase">Atenção</p><div id="insightLow" class="mt-1">--</div></div></div></div><div class="bg-blue-50 p-5 rounded-3xl border border-blue-100"><h4 class="text-xs font-bold text-blue-800 uppercase mb-2 flex items-center"><i data-lucide="lightbulb" class="w-3 h-3 mr-2"></i> Sugestão da IA</h4><p id="insightSuggestion" class="text-sm text-blue-900 leading-snug">Analisando seus dados...</p></div></div>
        <div class="bg-yellow-50 p-6 rounded-3xl border border-yellow-100 mb-8 text-center"><p class="text-sm text-gray-600 mb-4 font-medium">Sente que seus scores mudaram com esses dados?</p><button onclick="triggerNewCycle()" class="w-full bg-will-yellow text-black font-bold py-3 rounded-xl shadow-lg hover:shadow-xl transition transform active:scale-95">Aceitar & Atualizar Ciclo</button></div>
    </section>

    <!-- TELA 3: SETUP -->
    <section id="screenSetup" class="screen-section max-w-md mx-auto p-6">
        <header class="mb-6 pt-4"><h2 class="text-2xl font-bold text-gray-900 mb-1">Calibragem 🧭</h2><p class="text-gray-500 text-sm">Preencha para ganhar 300 XP.</p></header>
        <div id="wheelContainer" class="grid grid-cols-4 gap-3 mb-6"></div>
        <div class="mb-6"><label class="block text-xs font-bold text-gray-500 mb-3 uppercase tracking-wide">Escolha até 3 Focos (XP Dobrado)</label><div id="focusSelector" class="flex flex-wrap gap-2"></div></div>
        <div class="mb-8 bg-white p-6 rounded-3xl shadow-sm border border-gray-100"><label class="block text-xs font-bold text-gray-900 mb-3 uppercase tracking-wide">Meta SMART</label><textarea id="focusInput" onblur="saveFocus(this.value)" class="w-full p-4 bg-gray-50 border-2 border-gray-100 rounded-2xl focus:border-black focus:bg-white outline-none transition font-medium text-gray-800" rows="2" placeholder="Sua meta específica..."></textarea></div>
        <button onclick="navigate('screenAgenda')" class="btn-primary w-full py-4 flex justify-center items-center text-lg">Salvar e Ir <i data-lucide="arrow-right" class="ml-2 w-5 h-5"></i></button>
    </section>

    <!-- TELA 4: AGENDA (Com FAB) -->
    <section id="screenAgenda" class="screen-section max-w-md mx-auto p-4 relative min-h-screen">
        <header class="mb-4 pt-2"><h2 class="text-2xl font-bold text-gray-900 mb-4 px-2">Missões do Dia 🔥</h2><div id="dayTabsContainer" class="flex space-x-2 overflow-x-auto pb-4 px-1 scrollbar-hide"></div></header>
        <div class="bg-white p-5 rounded-3xl shadow-sm border border-gray-100 mb-8 overflow-x-auto"><div id="agendaHabits" class="habit-grid"></div></div>
        <div id="agendaListContainer" class="pb-24 px-1"></div>
        <button onclick="openMissionModal('create')" class="fixed bottom-24 right-6 bg-will-yellow text-black p-4 rounded-full shadow-2xl z-30 transform hover:scale-110 transition active:scale-95 border-2 border-black"><i data-lucide="plus" class="w-6 h-6"></i></button>
    </section>

    <!-- TELA 5: HALL DA FAMA -->
    <section id="screenReview" class="screen-section max-w-md mx-auto p-6">
        <header class="mb-6 pt-4"><h2 class="text-2xl font-bold text-gray-900 mb-2">Hall da Fama 🏆</h2><p class="text-gray-500 font-medium text-sm">Seus Emblemas e Reflexões.</p></header>
        <div class="mb-8"><h3 class="text-xs font-bold text-gray-400 uppercase tracking-wide mb-3">Conquistas</h3><div id="badgeContainer" class="grid grid-cols-3 gap-3"></div></div>
        <div class="space-y-6">
            <div class="bg-yellow-50 p-5 rounded-3xl border-2 border-yellow-100"><label class="block text-xs font-bold text-yellow-900 mb-2 uppercase flex items-center"><i data-lucide="star" class="w-3 h-3 mr-2"></i> Vitórias (+500 XP)</label><textarea id="reviewWins" onblur="saveReview('wins', this.value)" class="w-full p-3 bg-white border-0 rounded-xl text-gray-800 text-sm font-medium placeholder-yellow-300 focus:ring-2 focus:ring-yellow-400 outline-none" rows="2" placeholder="O que você mandou bem?"></textarea></div>
            <div class="bg-gray-100 p-5 rounded-3xl border-2 border-gray-200"><label class="block text-xs font-bold text-gray-900 mb-2 uppercase flex items-center"><i data-lucide="book-open" class="w-3 h-3 mr-2"></i> Aprendizados</label><textarea id="reviewLearn" onblur="saveReview('learn', this.value)" class="w-full p-3 bg-white border-0 rounded-xl text-gray-800 text-sm font-medium placeholder-gray-400 focus:ring-2 focus:ring-gray-400 outline-none" rows="2" placeholder="O que pode melhorar?"></textarea></div>
        </div>
        <div class="mt-8 pb-8"><button onclick="triggerNewCycle()" class="w-full bg-white border-2 border-black text-black py-4 rounded-full font-bold hover:bg-gray-50 transition transform active:scale-95">Iniciar Novo Ciclo (Calculado)</button></div>
    </section>

    <!-- NAVBAR -->
    <nav class="fixed bottom-6 left-6 right-6 bg-white border border-gray-100 py-3 px-2 rounded-3xl flex justify-between items-center z-50 shadow-2xl shadow-gray-200/50">
        <div class="nav-item flex flex-col items-center justify-center cursor-pointer py-2 flex-1 active" onclick="navigate('screenDashboard')"><i data-lucide="home" class="w-6 h-6"></i></div>
        <div class="nav-item flex flex-col items-center justify-center cursor-pointer py-2 flex-1" onclick="navigate('screenSetup')"><i data-lucide="sliders-horizontal" class="w-6 h-6"></i></div>
        <div class="nav-item flex flex-col items-center justify-center cursor-pointer py-2 flex-1" onclick="navigate('screenAgenda')"><i data-lucide="calendar" class="w-6 h-6"></i></div>
        <div class="nav-item flex flex-col items-center justify-center cursor-pointer py-2 flex-1" onclick="navigate('screenEvolution')"><i data-lucide="bar-chart-2" class="w-6 h-6"></i></div>
        <div class="nav-item flex flex-col items-center justify-center cursor-pointer py-2 flex-1" onclick="navigate('screenReview')"><i data-lucide="trophy" class="w-6 h-6"></i></div>
    </nav>
</body>
</html>
