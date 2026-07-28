# CS-300-Data-Structures-and-Algorithms

# What was the problem you were solving in the projects for this course?
The problem I was solving was how to manage a list of college courses and their prerequisites in a way that allowed academic advisors to easily search, sort, and print course information. The system needed to support adding, deleting, inserting, and searching for courses so advisors could quickly access accurate course data for students.

# How did you approach the problem?
I approached the problem by comparing different data structures and evaluating how well they supported the program’s requirements. I learned that vectors are useful for ordered, index‑based access, while binary search trees provide efficient 
𝑂
(
log
⁡
𝑛
)
 insertion and lookup when maintaining sorted order. For one project, I performed a runtime analysis and determined that a hash table was the best choice because it offers fast average‑case lookup and insertion 
𝑂
(
1
)
, allows the file to be processed in a single pass, supports quick searching by course number, and scales well for larger datasets. Understanding these differences helped me design the program with efficiency in mind from the start.

# How did you overcome any roadbloacks you encountered while going through the sctivities or project?
One roadblock I encountered was getting the formatting right when parsing the input file before inserting data into the structure. I overcame this by using string functions to trim whitespace and clean the input so each course and prerequisite could be processed correctly.

# How has your work on this project expanded your approach to designing software and developing programs?
This project expanded my approach by showing me the importance of understanding data structures before implementation. It changed the way I design programs because it made me think about efficiency early in the process instead of relying on trial‑and‑error coding.

# How has your work on this project evolved the way you write programs that are maintainable, readable, and adaptable?
This project improved my coding practices by helping me avoid unnecessary complexity. Keeping the design simple and focused led to more modular code, which is easier to read, maintain, and update in the future.
