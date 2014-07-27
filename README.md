---This-is-a-markdown-file
==========================

Data science coursera
% Find Indices of Positive and Negative Examples
pos = find(y==1); neg = find(y == 0);
% Plot Examples
plot(X(pos, 1), X(pos, 2), 'r+','LineWidth', 2, ...
'MarkerSize', 7);
plot(X(neg, 1), X(neg, 2), 'go','LineWidth', 2, ... 
    'MarkerSize', 7);
