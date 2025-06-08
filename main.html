<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cover Letter Generator</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <!-- jsPDF CDN for PDF generation -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6; /* Light gray background */
        }
        /* Style for clickable links in the textarea */
        .clickable-link {
            color: #2563eb; /* Blue color for links */
            text-decoration: underline;
        }
    </style>
</head>
<body class="p-4 sm:p-6 md:p-8 bg-gray-100 min-h-screen flex items-center justify-center">
    <div class="max-w-4xl w-full bg-white rounded-xl shadow-lg p-6 sm:p-8 md:p-10 border border-gray-200">
        <h1 class="text-3xl font-bold text-center text-gray-800 mb-6">Cover Letter Generator</h1>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-8">
            <!-- Left Column for Inputs -->
            <div class="space-y-4">
                <div>
                    <label for="inputDate" class="block text-sm font-medium text-gray-700 mb-1">Date</label>
                    <input type="date" id="inputDate" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500 text-gray-900" value="">
                </div>
                <div>
                    <label for="inputHiringManagerName" class="block text-sm font-medium text-gray-700 mb-1">Hiring Manager Name (Optional)</label>
                    <input type="text" id="inputHiringManagerName" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500 text-gray-900" placeholder="e.g., Jane Doe">
                </div>
                <div>
                    <label for="inputHiringManagerTitle" class="block text-sm font-medium text-gray-700 mb-1">Hiring Manager Title</label>
                    <input type="text" id="inputHiringManagerTitle" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500 text-gray-900" placeholder="e.g., Talent Acquisition Specialist">
                </div>
                <div>
                    <label for="inputCompanyName" class="block text-sm font-medium text-gray-700 mb-1">Company Name</label>
                    <input type="text" id="inputCompanyName" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500 text-gray-900" placeholder="e.g., Tech Innovations Inc.">
                </div>
            </div>

            <!-- Right Column for Inputs -->
            <div class="space-y-4">
                <div>
                    <label for="inputJobTitle" class="block text-sm font-medium text-gray-700 mb-1">Job Title</label>
                    <input type="text" id="inputJobTitle" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500 text-gray-900" placeholder="e.g., Junior Software Engineer">
                </div>
                <div>
                    <label for="inputPlatform" class="block text-sm font-medium text-gray-700 mb-1">Platform (where you saw ad)</label>
                    <input type="text" id="inputPlatform" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500 text-gray-900" placeholder="e.g., LinkedIn, Company Website">
                </div>
                <div>
                    <label for="inputCompanyCommitment" class="block text-sm font-medium text-gray-700 mb-1">Company's Commitment (e.g., innovation in AI)</label>
                    <input type="text" id="inputCompanyCommitment" class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500 text-gray-900" placeholder="e.g., solving complex real-world problems">
                </div>
            </div>
        </div>

        <button id="generateBtn" class="w-full bg-blue-600 hover:bg-blue-700 text-white font-semibold py-3 px-6 rounded-md shadow-md transition-all duration-300 ease-in-out transform hover:scale-105 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-offset-2 mb-6">
            Generate Cover Letter
        </button>

        <div id="outputContainer" class="hidden">
            <h2 class="text-xl font-semibold text-gray-800 mb-3">Generated Cover Letter:</h2>
            <div id="coverLetterDisplay" class="w-full p-4 border border-gray-300 rounded-md bg-gray-50 text-gray-800 resize-y mb-4 whitespace-pre-wrap"></div>
            <div class="flex flex-col sm:flex-row gap-4">
                <button id="copyBtn" class="w-full sm:w-1/2 bg-green-600 hover:bg-green-700 text-white font-semibold py-2 px-4 rounded-md shadow-md transition-all duration-300 ease-in-out transform hover:scale-105 focus:outline-none focus:ring-2 focus:ring-green-500 focus:ring-offset-2">
                    Copy to Clipboard
                </button>
                <button id="downloadPdfBtn" class="w-full sm:w-1/2 bg-red-600 hover:bg-red-700 text-white font-semibold py-2 px-4 rounded-md shadow-md transition-all duration-300 ease-in-out transform hover:scale-105 focus:outline-none focus:ring-2 focus:ring-red-500 focus:ring-offset-2">
                    Download as PDF
                </button>
            </div>
        </div>

        <!-- Custom Alert Message Box -->
        <div id="messageBox" class="fixed inset-0 bg-gray-600 bg-opacity-50 flex items-center justify-center hidden">
            <div class="bg-white p-6 rounded-lg shadow-xl max-w-sm w-full text-center">
                <p id="messageText" class="text-gray-800 text-lg font-medium mb-4"></p>
                <button id="messageBoxCloseBtn" class="bg-blue-600 hover:bg-blue-700 text-white font-semibold py-2 px-4 rounded-md">OK</button>
            </div>
        </div>

    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const inputDate = document.getElementById('inputDate');
            const inputHiringManagerName = document.getElementById('inputHiringManagerName');
            const inputHiringManagerTitle = document.getElementById('inputHiringManagerTitle');
            const inputCompanyName = document.getElementById('inputCompanyName');
            const inputJobTitle = document.getElementById('inputJobTitle');
            const inputPlatform = document.getElementById('inputPlatform');
            const inputCompanyCommitment = document.getElementById('inputCompanyCommitment');
            const generateBtn = document.getElementById('generateBtn');
            const coverLetterDisplay = document.getElementById('coverLetterDisplay');
            const outputContainer = document.getElementById('outputContainer');
            const copyBtn = document.getElementById('copyBtn');
            const downloadPdfBtn = document.getElementById('downloadPdfBtn'); // Get reference to the new button
            const messageBox = document.getElementById('messageBox');
            const messageText = document.getElementById('messageText');
            const messageBoxCloseBtn = document.getElementById('messageBoxCloseBtn');

            // Set today's date as default
            const today = new Date();
            const yyyy = today.getFullYear();
            const mm = String(today.getMonth() + 1).padStart(2, '0'); // Months start at 0!
            const dd = String(today.getDate()).padStart(2, '0');
            inputDate.value = `${yyyy}-${mm}-${dd}`;

            // Function to show custom message box
            function showMessageBox(message) {
                messageText.textContent = message;
                messageBox.classList.remove('hidden');
            }

            // Close message box
            messageBoxCloseBtn.addEventListener('click', () => {
                messageBox.classList.add('hidden');
            });

            generateBtn.addEventListener('click', () => {
                const date = inputDate.value;
                const hiringManagerName = inputHiringManagerName.value.trim();
                const hiringManagerTitle = inputHiringManagerTitle.value.trim();
                const companyName = inputCompanyName.value.trim();
                const jobTitle = inputJobTitle.value.trim();
                const platform = inputPlatform.value.trim();
                const companyCommitment = inputCompanyCommitment.value.trim();

                // Basic validation updated to exclude company address
                if (!date || !hiringManagerTitle || !companyName || !jobTitle || !platform || !companyCommitment) {
                    showMessageBox('Please fill in all required fields (marked by placeholders).');
                    return;
                }

                const managerSalutation = hiringManagerName ? `Dear ${hiringManagerName},` : `Dear ${hiringManagerTitle ? hiringManagerTitle : 'Hiring Team'},`;

                // Use <a> tags for clickable links. The content is set using innerHTML
                const coverLetterHtmlContent = `Tim Sinyakov
(+64) 27 53 97650 | timsinyakov13@gmail.com | <a href="https://linkedin.com/in/timsinyakov" target="_blank" class="clickable-link">linkedin.com/in/timsinyakov</a> | <a href="https://github.com/timsinyakov" target="_blank" class="clickable-link">github.com/timsinyakov</a>

${date}

${hiringManagerName ? hiringManagerName + '<br>' : ''}${hiringManagerTitle}
${companyName}

Subject: Application for ${jobTitle} - Tim Sinyakov

${managerSalutation}

I am writing to express my strong interest in the ${jobTitle} position at ${companyName}, as advertised on ${platform}. As a Computer Science graduate from the University of Auckland, with practical experience in full-stack development and automation, I am eager to contribute to your innovative team.

My internships at Fonterra and JustBlack Projects and Solutions, coupled with impactful projects, have equipped me with a robust skill set. At Fonterra, I supported AI proof-of-concept projects, contributing to one that was successfully deployed and saved an estimated $50,000. My "Devmarket.nz" project involved developing an automated Python web scraper and a Flask-based backend with MSSQL, alongside a comprehensive front-end for job market insights. Additionally, I gained experience with the MERN stack and RESTful API development as a Backend Developer for the WDCC ASPA project, and successfully dockerized and deployed a Node.js application on Azure for "Run Journal." I am proficient in languages including Python, JavaScript, TypeScript, and C#, and have practical experience with technologies such as Flask, React.js, Node.js, Docker, and Azure.

I am particularly drawn to ${companyName}'s commitment to ${companyCommitment}. My analytical mindset and dedication to continuous learning align well with your objectives.

I have attached my resume for your review and welcome the opportunity to discuss how my experience and skills can benefit ${companyName}.

Sincerely,

Tim Sinyakov`;

                coverLetterDisplay.innerHTML = coverLetterHtmlContent; // Set innerHTML
                outputContainer.classList.remove('hidden');
            });

            copyBtn.addEventListener('click', () => {
                // To copy the text, we'll create a temporary textarea,
                // populate it with the plain text, copy from it, then remove it.
                const tempTextArea = document.createElement('textarea');
                tempTextArea.value = coverLetterDisplay.innerText; // Get plain text from the div
                document.body.appendChild(tempTextArea);
                tempTextArea.select();
                try {
                    document.execCommand('copy');
                    showMessageBox('Cover letter copied to clipboard!');
                } catch (err) {
                    showMessageBox('Failed to copy. Please copy manually.');
                    console.error('Failed to copy text: ', err);
                } finally {
                    document.body.removeChild(tempTextArea);
                }
            });

            downloadPdfBtn.addEventListener('click', () => {
                const { jsPDF } = window.jspdf; // Get jsPDF from the window object
                const doc = new jsPDF();

                const textContent = coverLetterDisplay.innerText; // Get the plain text content
                const lines = doc.splitTextToSize(textContent, 180); // Split text into lines that fit within 180 units width

                let y = 20; // Starting Y position
                const lineHeight = 7; // Line height
                const margin = 10; // Left/Right margin

                doc.setFont("helvetica", "normal");
                doc.setFontSize(11);

                lines.forEach(line => {
                    if (y + lineHeight > doc.internal.pageSize.height - margin) {
                        doc.addPage();
                        y = 20; // Reset Y for new page
                    }
                    doc.text(line, margin, y);
                    y += lineHeight;
                });

                doc.save('cover_letter.pdf');
                showMessageBox('Cover letter downloaded as PDF!');
            });
        });
    </script>
</body>
</html>
