###penis
/* Centering the resume and LinkedIn container */
.resume-linkedin-container {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
    margin: 20px auto;
}

/* Styling for the resume box */
.resume-box {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100px;
    width: 150px;
    border: 2px solid #ddd;
    border-radius: 8px;
    background-color: #f4f4f4;
    transition: background-color 0.3s ease, color 0.3s ease;
    text-align: center;
    cursor: pointer;
}

.resume-box:hover {
    background-color: #007BFF;
    color: #fff;
}

/* Styling for the LinkedIn logo */
.linkedin-logo {
    width: 50px;
    cursor: pointer;
    transition: transform 0.3s ease;
}

.linkedin-logo:hover {
    transform: scale(1.1);
}

/* Project card styling */
.project-card {
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 20px;
    margin: 15px auto;
    background-color: #f4f4f4;
    transition: transform 0.3s ease, background-color 0.3s ease;
    position: relative;
    max-width: 900px;
}

.project-card:hover {
    background-color: #333;
    transform: translateY(-10px);
    cursor: pointer;
}

.project-card a {
    text-decoration: none;
    color: inherit;
}

.project-card:hover .project-content h3, 
.project-card:hover .project-content p {
    color: #fff;
}

.download-icon {
    position: absolute;
    top: 10px;
    right: 10px;
    width: 30px;
    height: 30px;
    cursor: pointer;
    transition: transform 0.3s ease;
}

.download-icon:hover {
    transform: scale(1.1);
}

/* Skills section styling */
#about h2 {
    text-align: center;
    margin-bottom: 20px;
}

.skills-container {
    display: flex;
    justify-content: center;
    gap: 20px;
}

.skill-box {
    border: 2px solid #ddd;
    border-radius: 8px;
    padding: 10px 20px;
    background-color: #f4f4f4;
    font-size: 18px;
    font-weight: bold;
    text-align: center;
    width: 100px;
    transition: background-color 0.3s ease, transform 0.3s ease;
}

.skill-box:hover {
    background-color: #007BFF;
    color: white;
    transform: scale(1.05);
}
