<!doctype html>
<html lang="en" class="h-full">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>iSteps Food Processing Quiz</title>
  <script src="https://cdn.tailwindcss.com/3.4.17"></script>
  <script src="/_sdk/element_sdk.js"></script>
  <script src="/_sdk/data_sdk.js"></script>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&amp;display=swap" rel="stylesheet">
  <style>
    * { font-family: 'Poppins', sans-serif; }
    .choice-btn { transition: all 0.2s ease; }
    .choice-btn:hover:not(:disabled) { transform: translateY(-2px); }
    .correct-answer { background: linear-gradient(135deg, #10b981, #059669) !important; color: white !important; border-color: #059669 !important; }
    .wrong-answer { background: linear-gradient(135deg, #ef4444, #dc2626) !important; color: white !important; border-color: #dc2626 !important; }
    .progress-bar { transition: width 0.5s ease; }
    @keyframes fadeIn { from { opacity: 0; transform: translateY(10px); } to { opacity: 1; transform: translateY(0); } }
    .fade-in { animation: fadeIn 0.4s ease forwards; }
    @keyframes pulse { 0%, 100% { transform: scale(1); } 50% { transform: scale(1.05); } }
    .pulse { animation: pulse 0.5s ease; }
  </style>
  <style>body { box-sizing: border-box; }</style>
 </head>
 <body class="h-full bg-gradient-to-br from-emerald-900 via-teal-800 to-cyan-900 overflow-auto">
  <div id="app-wrapper" class="w-full min-h-full p-4 md:p-8">
   <div class="max-w-3xl mx-auto">
    <!-- Entry Screen -->
    <div id="entry-screen" class="bg-white/95 backdrop-blur rounded-3xl shadow-2xl p-8 fade-in">
     <div class="text-center mb-8">
      <div class="inline-flex items-center justify-center w-20 h-20 bg-gradient-to-br from-emerald-500 to-teal-600 rounded-2xl mb-4 shadow-lg">
       <span class="text-4xl">🍽️</span>
      </div>
      <h1 id="main-title" class="text-3xl font-bold text-gray-800 mb-2">Food Processing &amp; Preservation Quiz</h1>
      <p id="subject-code-display" class="text-emerald-600 font-semibold text-lg">FET 227</p>
     </div>
     <form id="entry-form" class="space-y-5">
      <div>
       <label class="block text-sm font-semibold text-gray-700 mb-2">Full Name</label> <input type="text" id="student-name" required placeholder="Enter your full name" class="w-full px-4 py-3 rounded-xl border-2 border-gray-200 focus:border-emerald-500 focus:ring-4 focus:ring-emerald-100 outline-none transition-all text-gray-800">
      </div>
      <div class="grid grid-cols-2 gap-4">
       <div>
        <label class="block text-sm font-semibold text-gray-700 mb-2">Grade Level</label> <input type="text" id="student-grade" required placeholder="e.g., Grade 11" class="w-full px-4 py-3 rounded-xl border-2 border-gray-200 focus:border-emerald-500 focus:ring-4 focus:ring-emerald-100 outline-none transition-all text-gray-800">
       </div>
       <div>
        <label class="block text-sm font-semibold text-gray-700 mb-2">Section</label> <input type="text" id="student-section" required placeholder="e.g., Section A" class="w-full px-4 py-3 rounded-xl border-2 border-gray-200 focus:border-emerald-500 focus:ring-4 focus:ring-emerald-100 outline-none transition-all text-gray-800">
       </div>
      </div><button type="submit" class="w-full py-4 bg-gradient-to-r from-emerald-500 to-teal-600 text-white font-bold text-lg rounded-xl shadow-lg hover:shadow-xl hover:from-emerald-600 hover:to-teal-700 transition-all transform hover:-translate-y-0.5"> Start Quiz 🚀 </button>
     </form>
     <p class="text-center text-gray-500 text-sm mt-6">20 multiple choice questions • Answers are jumbled</p>
    </div><!-- Quiz Screen -->
    <div id="quiz-screen" class="hidden">
     <div class="bg-white/95 backdrop-blur rounded-3xl shadow-2xl overflow-hidden">
      <!-- Header -->
      <div class="bg-gradient-to-r from-emerald-500 to-teal-600 p-6 text-white">
       <div class="flex justify-between items-center mb-4">
        <span id="quiz-student-name" class="font-semibold"></span> <span id="quiz-progress-text" class="text-emerald-100">Question 1 of 20</span>
       </div>
       <div class="w-full bg-white/30 rounded-full h-3">
        <div id="progress-bar" class="progress-bar bg-white rounded-full h-3" style="width: 5%"></div>
       </div>
      </div><!-- Question Area -->
      <div class="p-6 md:p-8">
       <div id="question-container" class="fade-in">
        <h2 id="question-text" class="text-xl md:text-2xl font-bold text-gray-800 mb-6 leading-relaxed"></h2>
        <div id="choices-container" class="space-y-3"></div>
       </div>
       <div id="feedback-area" class="hidden mt-6 p-4 rounded-xl text-center">
        <p id="feedback-text" class="font-semibold text-lg"></p>
       </div><button id="next-btn" class="hidden w-full mt-6 py-4 bg-gradient-to-r from-emerald-500 to-teal-600 text-white font-bold text-lg rounded-xl shadow-lg hover:shadow-xl transition-all"> Next Question → </button>
      </div>
     </div><!-- Score Tracker & Timer -->
     <div class="mt-4 bg-white/20 backdrop-blur rounded-2xl p-4 flex justify-center gap-8 text-white">
      <div class="text-center">
       <p class="text-3xl font-bold" id="current-score">0</p>
       <p class="text-emerald-200 text-sm">Correct</p>
      </div>
      <div class="text-center">
       <p class="text-3xl font-bold" id="current-wrong">0</p>
       <p class="text-red-200 text-sm">Wrong</p>
      </div>
      <div class="text-center">
       <p class="text-3xl font-bold" id="timer-display">20:00</p>
       <p class="text-blue-200 text-sm">Time Left</p>
      </div>
     </div>
    </div><!-- Results Screen -->
    <div id="results-screen" class="hidden bg-white/95 backdrop-blur rounded-3xl shadow-2xl p-8 text-center fade-in">
     <div id="result-icon" class="text-8xl mb-4"></div>
     <h2 class="text-3xl font-bold text-gray-800 mb-2">Quiz Complete!</h2>
     <p id="result-student-name" class="text-emerald-600 font-semibold text-lg mb-6"></p>
     <div class="bg-gradient-to-br from-emerald-50 to-teal-50 rounded-2xl p-6 mb-6">
      <p class="text-6xl font-bold text-emerald-600 mb-2" id="final-score"></p>
      <p class="text-gray-600">out of 20 questions</p>
      <p id="percentage-display" class="text-2xl font-bold text-teal-600 mt-2"></p>
     </div>
     <div id="result-message" class="text-lg text-gray-700 mb-8"></div><!-- Performance Analysis -->
     <div class="bg-gradient-to-br from-blue-50 to-purple-50 rounded-2xl p-6 mb-6">
      <h3 class="text-xl font-bold text-gray-800 mb-6 text-left">📊 Performance Analysis</h3>
      <div class="grid grid-cols-2 gap-4 mb-6">
       <div class="bg-white rounded-xl p-4 text-center">
        <p class="text-emerald-600 font-bold text-2xl" id="accuracy-score">0%</p>
        <p class="text-gray-600 text-sm">Accuracy Rate</p>
       </div>
       <div class="bg-white rounded-xl p-4 text-center">
        <p class="text-purple-600 font-bold text-2xl" id="correct-count">0/20</p>
        <p class="text-gray-600 text-sm">Correct Answers</p>
       </div>
       <div class="bg-white rounded-xl p-4 text-center">
        <p class="text-red-600 font-bold text-2xl" id="wrong-count">0/20</p>
        <p class="text-gray-600 text-sm">Incorrect Answers</p>
       </div>
       <div class="bg-white rounded-xl p-4 text-center">
        <p class="text-blue-600 font-bold text-2xl" id="time-taken">Instant</p>
        <p class="text-gray-600 text-sm">Time Taken</p>
       </div>
      </div><!-- Performance Meter -->
      <div class="bg-white rounded-xl p-4">
       <p class="text-gray-700 font-semibold mb-3 text-left">Performance Level</p>
       <div class="w-full bg-gray-200 rounded-full h-4 overflow-hidden">
        <div id="performance-meter" class="h-4 rounded-full transition-all duration-500" style="width: 0%; background: linear-gradient(90deg, #ef4444, #f59e0b, #10b981);"></div>
       </div>
       <p id="performance-label" class="text-gray-600 text-sm mt-2 text-left">Loading...</p>
      </div>
     </div><!-- Feedback & Recommendations -->
     <div class="bg-amber-50 rounded-2xl p-6 mb-6 border-2 border-amber-200">
      <h3 class="text-lg font-bold text-gray-800 mb-4">💡 Recommendations</h3>
      <ul id="recommendations-list" class="space-y-2 text-left text-gray-700">
       <li class="flex items-start"><span class="text-amber-600 font-bold mr-3">•</span><span>Review the material and try again</span></li>
      </ul>
     </div>
     <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
      <a href="https://www.youtube.com/watch?v=9IK9a01vyy4" target="_blank" rel="noopener noreferrer" class="py-4 bg-gradient-to-r from-blue-500 to-blue-600 text-white font-bold text-lg rounded-xl shadow-lg hover:shadow-xl transition-all text-center"> Review Material 📖 </a> <button id="submit-btn" class="py-4 bg-gradient-to-r from-purple-500 to-purple-600 text-white font-bold text-lg rounded-xl shadow-lg hover:shadow-xl transition-all"> Submit to Teacher 📤 </button>
     </div><button id="retake-btn" class="w-full mt-4 py-4 bg-gradient-to-r from-emerald-500 to-teal-600 text-white font-bold text-lg rounded-xl shadow-lg hover:shadow-xl transition-all"> Take Quiz Again 🔄 </button>
    </div>
   </div>
  </div>
  <script>
    // Quiz Questions Data
    const originalQuestions = [
      {
        question: "Which term refers to the process of retaining food over a period of time without loss of color, texture, flavor, and nutritive value?",
        choices: ["Food transformation", "Food preservation", "Food engineering", "Food consumption"],
        correct: 1
      },
      {
        question: "Perishable foods are defined as those that last for:",
        choices: ["2 months to 6 months", "More than 6 months", "2 days to 1 week", "Indefinite periods"],
        correct: 2
      },
      {
        question: "Which of the following is an example of a shelf-stable food?",
        choices: ["Milk", "Bread", "Fruits", "Grains"],
        correct: 3
      },
      {
        question: "What is the primary purpose of 'Asepsis' in preservation?",
        choices: ["To kill existing bacteria", "To keep out microorganisms", "To add flavor to food", "To remove water from food"],
        correct: 1
      },
      {
        question: "Which method is classified as 'Bactericidal'?",
        choices: ["Freezing", "Salting", "Canning", "Smoking"],
        correct: 2
      },
      {
        question: "Bacteriostatic methods are based on:",
        choices: ["Killing all microorganisms", "Prevention of multiplication of microorganisms", "Using radiation to destroy cells", "High-temperature sterilization"],
        correct: 1
      },
      {
        question: "Which chemical is commonly used to preserve meats?",
        choices: ["Sulphites", "Nitrates and Nitrites", "Phenolase", "Acetic acid"],
        correct: 1
      },
      {
        question: "How does salting preserve food like fresh fish?",
        choices: ["It adds essential vitamins", "It draws out moisture to prevent growth", "It cooks the fish chemically", "It kills microbes with high acidity"],
        correct: 1
      },
      {
        question: "Vacuum packing prevents spoilage primarily because:",
        choices: ["It keeps the food frozen", "It adds carbon dioxide", "There is no air for microbes to grow", "It uses gamma-rays"],
        correct: 2
      },
      {
        question: "At what temperature range are microorganisms typically rendered inactive during freezing?",
        choices: ["0°C to 5°C", "-5°C to 0°C", "-18°C or below", "10°C to 15°C"],
        correct: 2
      },
      {
        question: "Waxing is commonly applied to which of the following?",
        choices: ["Grains and pulses", "Meat and poultry", "Apples and eggplants", "Milk and juices"],
        correct: 2
      },
      {
        question: "Pasteurization is a heat treatment that kills most bacteria without affecting:",
        choices: ["Moisture content", "Taste and nutritional value", "The color of the packaging", "The salt levels"],
        correct: 1
      },
      {
        question: "Which preservation method uses Gamma-rays from isotopes?",
        choices: ["Smoking", "Irradiation", "Blanching", "Extrusion"],
        correct: 1
      },
      {
        question: "What is the main purpose of blanching vegetables?",
        choices: ["To act as a final preservation step", "To destroy enzymatic activity prior to further processing", "To remove all moisture", "To add artificial flavors"],
        correct: 1
      },
      {
        question: "Smoking is mainly used for which types of food?",
        choices: ["Grains and cereals", "Fish, meat, and bananas", "Milk and yogurt", "Pickled vegetables"],
        correct: 1
      },
      {
        question: "Food processing is defined as transforming raw ingredients into:",
        choices: ["Soil nutrients", "Food for consumption", "Raw materials for textiles", "Hazardous chemicals"],
        correct: 1
      },
      {
        question: "Which of these is NOT a preservation measure?",
        choices: ["Drying", "Freezing", "Extrusion", "Canning"],
        correct: 2
      },
      {
        question: "Dehydration (drying) works by:",
        choices: ["Increasing water activity", "Reducing water activity to inhibit microbial growth", "Injecting hot air into the food cells", "Adding sugar solutions"],
        correct: 1
      },
      {
        question: "Chilling reduces the temperature of a food to between:",
        choices: ["-18°C and -25°C", "0°C and 8°C", "20°C and 30°C", "50°C and 60°C"],
        correct: 1
      },
      {
        question: "Which factor does NOT influence blanching time?",
        choices: ["Type of fruit or vegetable", "Size of the pieces of food", "Blanching temperature", "The brand of the packaging"],
        correct: 3
      }
    ];

    // State
    let currentQuestionIndex = 0;
    let score = 0;
    let wrongCount = 0;
    let shuffledQuestions = [];
    let studentInfo = { name: '', grade: '', section: '' };
    let answered = false;
    let quizStartTime = 0;
    let quizEndTime = 0;
    let timeLeft = 1200; // 20 minutes in seconds
    let timerInterval = null;

    // Config
    const defaultConfig = {
      quiz_title: "Food Processing & Preservation Quiz",
      subject_code: "FET 227",
      background_color: "#064e3b",
      surface_color: "#ffffff",
      text_color: "#1f2937",
      primary_action_color: "#10b981",
      secondary_action_color: "#0d9488"
    };

    // Shuffle array helper
    function shuffleArray(array) {
      const newArray = [...array];
      for (let i = newArray.length - 1; i > 0; i--) {
        const j = Math.floor(Math.random() * (i + 1));
        [newArray[i], newArray[j]] = [newArray[j], newArray[i]];
      }
      return newArray;
    }

    // Prepare questions with shuffled choices
    function prepareQuestions() {
      shuffledQuestions = shuffleArray(originalQuestions).map(q => {
        const correctAnswer = q.choices[q.correct];
        const shuffledChoices = shuffleArray(q.choices);
        const newCorrectIndex = shuffledChoices.indexOf(correctAnswer);
        return {
          question: q.question,
          choices: shuffledChoices,
          correct: newCorrectIndex
        };
      });
    }

    // Display current question
    function displayQuestion() {
      const q = shuffledQuestions[currentQuestionIndex];
      document.getElementById('question-text').textContent = `${currentQuestionIndex + 1}. ${q.question}`;
      
      const choicesContainer = document.getElementById('choices-container');
      choicesContainer.innerHTML = '';
      
      const letters = ['A', 'B', 'C', 'D'];
      q.choices.forEach((choice, index) => {
        const btn = document.createElement('button');
        btn.className = 'choice-btn w-full text-left p-4 rounded-xl border-2 border-gray-200 hover:border-emerald-400 hover:bg-emerald-50 font-medium text-gray-700 transition-all';
        btn.innerHTML = `<span class="inline-flex items-center justify-center w-8 h-8 rounded-lg bg-emerald-100 text-emerald-700 font-bold mr-3">${letters[index]}</span>${choice}`;
        btn.onclick = () => selectAnswer(index);
        choicesContainer.appendChild(btn);
      });

      document.getElementById('quiz-progress-text').textContent = `Question ${currentQuestionIndex + 1} of 20`;
      document.getElementById('progress-bar').style.width = `${((currentQuestionIndex + 1) / 20) * 100}%`;
      
      document.getElementById('feedback-area').classList.add('hidden');
      document.getElementById('next-btn').classList.add('hidden');
      answered = false;

      // Re-trigger animation
      const container = document.getElementById('question-container');
      container.classList.remove('fade-in');
      void container.offsetWidth;
      container.classList.add('fade-in');
    }

    // Handle answer selection
    function selectAnswer(selectedIndex) {
      if (answered) return;
      answered = true;

      const q = shuffledQuestions[currentQuestionIndex];
      const buttons = document.querySelectorAll('.choice-btn');
      const feedbackArea = document.getElementById('feedback-area');
      const feedbackText = document.getElementById('feedback-text');

      buttons.forEach((btn, index) => {
        btn.disabled = true;
        if (index === q.correct) {
          btn.classList.add('correct-answer');
        } else if (index === selectedIndex && selectedIndex !== q.correct) {
          btn.classList.add('wrong-answer');
        }
      });

      if (selectedIndex === q.correct) {
        score++;
        timeLeft += 3; // Add 3 seconds for correct answer
        feedbackArea.className = 'mt-6 p-4 rounded-xl text-center bg-emerald-100';
        feedbackText.innerHTML = '✅ Correct! Great job! (+3 seconds ⏱️)';
        feedbackText.className = 'font-semibold text-lg text-emerald-700';
      } else {
        wrongCount++;
        feedbackArea.className = 'mt-6 p-4 rounded-xl text-center bg-red-100';
        feedbackText.innerHTML = `❌ Incorrect. The correct answer is: <strong>${q.choices[q.correct]}</strong>`;
        feedbackText.className = 'font-semibold text-lg text-red-700';
      }

      feedbackArea.classList.remove('hidden');
      document.getElementById('current-score').textContent = score;
      document.getElementById('current-wrong').textContent = wrongCount;

      const nextBtn = document.getElementById('next-btn');
      nextBtn.classList.remove('hidden');
      nextBtn.textContent = currentQuestionIndex < 19 ? 'Next Question →' : 'View Results 🎉';
    }

    // Calculate time taken
    function formatTimeTaken(seconds) {
      if (seconds < 60) return `${seconds}s`;
      const minutes = Math.floor(seconds / 60);
      const secs = seconds % 60;
      return `${minutes}m ${secs}s`;
    }

    // Update timer display
    function updateTimerDisplay() {
      const minutes = Math.floor(timeLeft / 60);
      const seconds = timeLeft % 60;
      const display = `${minutes}:${seconds.toString().padStart(2, '0')}`;
      document.getElementById('timer-display').textContent = display;

      // Change color based on time remaining
      const timerEl = document.getElementById('timer-display');
      if (timeLeft <= 300) { // 5 minutes or less
        timerEl.classList.add('text-red-400');
        timerEl.classList.remove('text-blue-400');
      } else {
        timerEl.classList.remove('text-red-400');
        timerEl.classList.add('text-blue-400');
      }
    }

    // Start timer
    function startTimer() {
      timeLeft = 1200; // Reset to 20 minutes
      updateTimerDisplay();
      
      if (timerInterval) clearInterval(timerInterval);
      
      timerInterval = setInterval(() => {
        timeLeft--;
        updateTimerDisplay();

        if (timeLeft <= 0) {
          clearInterval(timerInterval);
          endQuizDueToTimeout();
        }
      }, 1000);
    }

    // End quiz due to timeout
    function endQuizDueToTimeout() {
      answered = true;
      document.querySelectorAll('.choice-btn').forEach(btn => btn.disabled = true);
      const feedbackArea = document.getElementById('feedback-area');
      feedbackArea.className = 'mt-6 p-4 rounded-xl text-center bg-red-100';
      const feedbackText = document.getElementById('feedback-text');
      feedbackText.innerHTML = '⏱️ Time\'s up! Quiz automatically submitted.';
      feedbackText.className = 'font-semibold text-lg text-red-700';
      feedbackArea.classList.remove('hidden');
      
      setTimeout(() => {
        showResults();
      }, 2000);
    }

    // Get performance feedback
    function getPerformanceFeedback(percentage) {
      if (percentage >= 90) {
        return {
          level: 'Excellent',
          recommendations: [
            '🎯 You have mastered food processing and preservation concepts!',
            '📚 Consider helping peers understand these topics.',
            '⭐ You\'re ready for advanced food science studies!'
          ]
        };
      } else if (percentage >= 75) {
        return {
          level: 'Good',
          recommendations: [
            '📖 Review preservation methods (canning, smoking, irradiation).',
            '🧪 Focus on understanding the science behind each technique.',
            '💪 Practice with real-world food preservation scenarios.'
          ]
        };
      } else if (percentage >= 60) {
        return {
          level: 'Fair',
          recommendations: [
            '📝 Review all preservation methods systematically.',
            '🔬 Study the difference between bactericidal and bacteriostatic methods.',
            '📚 Pay special attention to temperature ranges and chemical preservatives.'
          ]
        };
      } else {
        return {
          level: 'Need Improvement',
          recommendations: [
            '📚 Start with basic concepts: what is food preservation?',
            '🎓 Review lecture notes and textbook chapters systematically.',
            '✏️ Create flashcards for preservation methods and chemicals.',
            '🔄 Practice this quiz again after studying.'
          ]
        };
      }
    }

    // Show results
    async function showResults() {
      if (timerInterval) clearInterval(timerInterval);
      quizEndTime = Date.now();
      const timeTakenSeconds = Math.round((quizEndTime - quizStartTime) / 1000);

      document.getElementById('quiz-screen').classList.add('hidden');
      document.getElementById('results-screen').classList.remove('hidden');

      const percentage = Math.round((score / 20) * 100);
      document.getElementById('result-student-name').textContent = `${studentInfo.name} • ${studentInfo.grade} - ${studentInfo.section}`;
      document.getElementById('final-score').textContent = score;
      document.getElementById('percentage-display').textContent = `${percentage}%`;
      
      // Performance Analysis
      document.getElementById('accuracy-score').textContent = `${percentage}%`;
      document.getElementById('correct-count').textContent = `${score}/20`;
      document.getElementById('wrong-count').textContent = `${wrongCount}/20`;
      document.getElementById('time-taken').textContent = formatTimeTaken(timeTakenSeconds);

      // Performance meter
      const meter = document.getElementById('performance-meter');
      meter.style.width = `${percentage}%`;
      
      const feedback = getPerformanceFeedback(percentage);
      document.getElementById('performance-label').textContent = `${feedback.level} Performance`;

      // Recommendations
      const recList = document.getElementById('recommendations-list');
      recList.innerHTML = feedback.recommendations
        .map(rec => `<li class="flex items-start"><span class="text-amber-600 font-bold mr-3">•</span><span>${rec}</span></li>`)
        .join('');

      let icon, message;
      if (percentage >= 90) {
        icon = '🏆';
        message = 'Outstanding! You have excellent knowledge of food processing and preservation!';
      } else if (percentage >= 75) {
        icon = '🌟';
        message = 'Great work! You have a solid understanding of the subject!';
      } else if (percentage >= 60) {
        icon = '👍';
        message = 'Good effort! Review some topics to improve your score.';
      } else {
        icon = '📚';
        message = 'Keep studying! Review the material and try again.';
      }

      document.getElementById('result-icon').textContent = icon;
      document.getElementById('result-message').textContent = message;

      // Save result to Data SDK
      if (window.dataSdk) {
        const result = await window.dataSdk.create({
          student_name: studentInfo.name,
          grade: studentInfo.grade,
          section: studentInfo.section,
          score: score,
          total_questions: 20,
          percentage: percentage,
          date_taken: new Date().toISOString()
        });
        if (!result.isOk) {
          console.error('Failed to save quiz result');
        }
      }
    }

    // Reset quiz
    function resetQuiz() {
      currentQuestionIndex = 0;
      score = 0;
      wrongCount = 0;
      timeLeft = 1200;
      if (timerInterval) clearInterval(timerInterval);
      document.getElementById('current-score').textContent = '0';
      document.getElementById('current-wrong').textContent = '0';
      document.getElementById('timer-display').textContent = '20:00';
      document.getElementById('results-screen').classList.add('hidden');
      document.getElementById('entry-screen').classList.remove('hidden');
      document.getElementById('student-name').value = '';
      document.getElementById('student-grade').value = '';
      document.getElementById('student-section').value = '';
    }

    // Event Listeners
    document.getElementById('entry-form').addEventListener('submit', (e) => {
      e.preventDefault();
      studentInfo.name = document.getElementById('student-name').value.trim();
      studentInfo.grade = document.getElementById('student-grade').value.trim();
      studentInfo.section = document.getElementById('student-section').value.trim();

      document.getElementById('quiz-student-name').textContent = studentInfo.name;
      document.getElementById('entry-screen').classList.add('hidden');
      document.getElementById('quiz-screen').classList.remove('hidden');

      quizStartTime = Date.now();
      prepareQuestions();
      startTimer();
      displayQuestion();
    });

    document.getElementById('next-btn').addEventListener('click', () => {
      if (currentQuestionIndex < 19) {
        currentQuestionIndex++;
        displayQuestion();
      } else {
        showResults();
      }
    });

    document.getElementById('retake-btn').addEventListener('click', resetQuiz);

    // Submit to teacher
    document.getElementById('submit-btn').addEventListener('click', () => {
      const percentage = Math.round((score / 20) * 100);
      const message = `Quiz Results - ${studentInfo.name}\nGrade: ${studentInfo.grade} | Section: ${studentInfo.section}\n\nScore: ${score}/20 (${percentage}%)\nCorrect: ${score} | Incorrect: ${wrongCount}\n\nSubmitted: ${new Date().toLocaleString()}`;
      
      // Copy to clipboard
      navigator.clipboard.writeText(message).then(() => {
        const submitBtn = document.getElementById('submit-btn');
        const originalText = submitBtn.textContent;
        submitBtn.textContent = '✅ Copied to Clipboard!';
        submitBtn.style.background = 'linear-gradient(135deg, #10b981, #059669)';
        setTimeout(() => {
          submitBtn.textContent = originalText;
          submitBtn.style.background = '';
        }, 3000);
      }).catch(() => {
        alert('Failed to copy. Please try again.');
      });
    });

    // Element SDK & Data SDK Initialization
    const dataHandler = {
      onDataChanged(data) {
        // Quiz results are saved but not displayed in this view
      }
    };

    async function initApp() {
      if (window.dataSdk) {
        await window.dataSdk.init(dataHandler);
      }

      if (window.elementSdk) {
        window.elementSdk.init({
          defaultConfig,
          onConfigChange: async (config) => {
            const title = config.quiz_title || defaultConfig.quiz_title;
            const code = config.subject_code || defaultConfig.subject_code;
            document.getElementById('main-title').textContent = title;
            document.getElementById('subject-code-display').textContent = code;
          },
          mapToCapabilities: (config) => ({
            recolorables: [
              {
                get: () => config.background_color || defaultConfig.background_color,
                set: (v) => window.elementSdk.setConfig({ background_color: v })
              },
              {
                get: () => config.surface_color || defaultConfig.surface_color,
                set: (v) => window.elementSdk.setConfig({ surface_color: v })
              },
              {
                get: () => config.text_color || defaultConfig.text_color,
                set: (v) => window.elementSdk.setConfig({ text_color: v })
              },
              {
                get: () => config.primary_action_color || defaultConfig.primary_action_color,
                set: (v) => window.elementSdk.setConfig({ primary_action_color: v })
              },
              {
                get: () => config.secondary_action_color || defaultConfig.secondary_action_color,
                set: (v) => window.elementSdk.setConfig({ secondary_action_color: v })
              }
            ],
            borderables: [],
            fontEditable: undefined,
            fontSizeable: undefined
          }),
          mapToEditPanelValues: (config) => new Map([
            ["quiz_title", config.quiz_title || defaultConfig.quiz_title],
            ["subject_code", config.subject_code || defaultConfig.subject_code]
          ])
        });
      }
    }

    initApp();
  </script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9d7478879037fecd',t:'MTc3MjY2NDk1MS4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
