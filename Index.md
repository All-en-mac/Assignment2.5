Step 1: index.html Source Code
Create your index.html file and paste the following clean, semantic HTML code into it:

HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio - Alex Johnson</title>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Alex Johnson</h1>
        <p>Aspiring Full-Stack Web Developer & Technology Enthusiast</p>
    </header>

    <hr>

    <!-- About Me Section -->
    <section>
        <h2>About Me</h2>
        <p>Hello! Welcome to my personal introduction webpage. I am deeply passionate about learning web development and building creative solutions using clean, semantic code. When I'm not coding, I enjoy reading tech articles, hiking, and exploring open-source projects.</p>
    </section>

    <hr>

    <!-- Education Section -->
    <section>
        <h2>Education</h2>
        <h3>Bachelor of Science in Computer Science</h3>
        <p>
            <strong>Institution:</strong> Tech State University <br>
            <strong>Duration:</strong> 2022 – Expected May 2026
        </p>
    </section>

    <hr>

    <!-- Technical Skills Section -->
    <section>
        <h2>Technical Skills</h2>
        <ul>
            <li><strong>Languages:</strong> HTML5, CSS3, JavaScript</li>
            <li><strong>Tools & Platforms:</strong> Git, GitHub, VS Code, Chrome DevTools</li>
            <li><strong>Core Competencies:</strong> Semantic Markup, Version Control, Problem Solving</li>
        </ul>
    </section>

    <hr>

    <!-- Hobbies Section -->
    <section>
        <h2>Hobbies & Interests</h2>
        <p>In my spare time, I love engaging in activities that keep my mind sharp and creative:</p>
        <ul>
            <li>Digital Photography & Landscape Imaging</li>
            <li>Strategic Chess & Puzzle Solving</li>
            <li>Reading Science Fiction and Tech Literature</li>
        </ul>
    </section>

    <hr>

    <!-- Contact Information Section -->
    <section>
        <h2>Contact Information</h2>
        <p>Feel free to reach out to me via any of the channels below:</p>
        <ul>
            <li><strong>Email:</strong> <a href="mailto:alex.johnson@example.com">alex.johnson@example.com</a></li>
            <li><strong>GitHub:</strong> <a href="https://github.com" target="_blank">github.com/alexjohnson</a></li>
        </ul>
    </section>

</body>
</html>
Step 2: Git Commit & Push Instructions
To fulfill the final rule of committing your code to a Git repository and pushing it to GitHub, run these commands in your project's terminal:

Bash
# Check the status of your files
git status

# Stage the updated index.html file
git add index.html

# Commit the changes with a meaningful message
git commit -m "feat: complete HTML foundations mini-project index.html"

# Push the code to your remote GitHub repository
git push origin main
Submission Checklist
index.html file: Created and saved with all required sections and semantic tags.

Local Verification: Opened in the browser via Live Server to ensure all headings, lists, and links render correctly.

GitHub Link: Submit your public GitHub repository URL (e.g., [https://github.com/YOUR-USERNAME/web-development-practice](https://github.com/YOUR-USERNAME/web-development-practice)) to complete your mini-project assignment