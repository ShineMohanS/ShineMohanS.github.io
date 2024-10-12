<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My MATLAB Assignments</title>
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
            padding: 10px 0;
            text-align: center;
        }
        main {
            margin: 20px;
        }
        section {
            background-color: #fff;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        a {
            color: #337ab7;
            text-decoration: none;
        }
    </style>
</head>
<body>

<header>
    <h1>My MATLAB Assignments</h1>
</header>

<main>
    <section>
        <h2>Assignment 1: Simulink Model of a Trapezoidal Signal</h2>
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
    </section>

    <section>
        <h2>Assignment 2: MATLAB Code for Boolean Expressions</h2>
        <p>This assignment involves generating Boolean expressions based on user inputs.</p>
        <p><a href="path/to/matlab-code.m" download>Download MATLAB Code</a></p>
        <pre>
% MATLAB code to generate Boolean expression
inputs = [1 0 1 0];
expr = sprintf('%d AND %d', inputs(1), inputs(2));
disp(['Boolean Expression: ' expr]);
        </pre>
    </section>

    <!-- Add more assignments as needed -->
</main>

</body>
</html>
