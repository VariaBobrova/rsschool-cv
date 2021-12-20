Varia Bobrova
Junior Frontend Developer

    Based in Kyiv, Ukraine
    tel: +38 050-952-93-62
    email: varia.bobrova@gmail.com
    LinkedIn
    Behance

Summary

After 10 years as a graphic and interface designer I'm ready for new challenges as a developer. Currently working toward the goal of having a career that combines design and development skills.
Skills

    HTML, CSS
    JavaScript basics
    C, Python, SQL basics
    UI/UX design and prototyping
    Photoshop, Illustrator, Sketch

Code example

    Given two points A and B at an 8x8 grid you should find out the number of different paths between points (moving one cell at a time either down or right). Input is given as a string formatted as "(x1 y1)(x2 y2)".

function travelChessboard(s) {
    let x = s[6] - s[1];
    let y = s[8] - s[3];  
    function f(n) { return (n == 1) ? 1 : (n * f(n - 1)) }   
    return (x == 0 || y == 0) ? 1 : f(x + y) / (f(x) * f(y));
}

Education

    Saint Petersburg State University of Telecommunications
    Engineer's degree

    CS50 Introduction to Computer Science

English

    B2 (Upper Intermediate)

