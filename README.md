<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shine Mohan's Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        main {
            margin: 20px;
        }
        .profile {
            background-color: #fff;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .profile img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
        }
        .profile h2 {
            margin: 10px 0;
            font-size: 24px;
        }
        .profile p {
            font-size: 16px;
            color: #666;
        }
        .showcase {
            background-color: #fff;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .showcase h2 {
            font-size: 22px;
            margin-bottom: 15px;
        }
        .assignment {
            background-color: #f9f9f9;
            padding: 15px;
            margin-bottom: 15px;
            border-radius: 5px;
        }
        .assignment pre {
            background-color: #eee;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
        a {
            color: #337ab7;
            text-decoration: none;
        }
    </style>
</head>
<body>

<header>
    <h1>Shine Mohan's Portfolio</h1>
</header>

<main>
    <!-- Profile Section -->
    <section class="profile">
        <img src="path/to/your-photo.jpg" alt="Shine Mohan">
        <h2>Shine Mohan</h2>
        <p>Software Developer and MATLAB Enthusiast. Passionate about creating innovative solutions through coding and technology.</p>
    </section>

    <!-- Showcase Section -->
    <section class="showcase">
        <h2>My Works</h2>

        <!-- Assignment 1 -->
        <div class="assignment">
            <h3>Assignment 1: Simulink Model of a Trapezoidal Signal</h3>
            <p>This assignment includes a Simulink model that generates a trapezoidal signal. The goal was to simulate, time-shift, and scale the signal.</p>
            <p><a href="path/to/simulink-file.slx" download>Download Simulink File</a></p>
            <p>MATLAB Code:</p>
            <pre>
% MATLAB code for trapezoidal signal
t = 0:0.01:10;
y = tripuls(t-5, 5);
plot(t, y);
xlabel('Time (s)');
ylabel('Amplitude');
            </pre>
        </div>

        <!-- Assignment 2 -->
        <div class="assignment">
            <h3>Assignment 2: MATLAB Code for Boolean Expressions</h3>
            <p>This assignment involves generating Boolean expressions based on user inputs.</p>
            <p><a href="path/to/matlab-code.m" download>Download MATLAB Code</a></p>
            <pre>
% MATLAB code to generate Boolean expression
inputs = [1 0 1 0];
expr = sprintf('%d AND %d', inputs(1), inputs(2));
disp(['Boolean Expression: ' expr]);
            </pre>
        </div>

        <!-- Add more assignments or works as needed -->
    </section>
</main>

</body>
</html>
