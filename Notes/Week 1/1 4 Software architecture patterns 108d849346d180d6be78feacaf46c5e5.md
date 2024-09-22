# 1.4 Software architecture patterns.

Created: September 21, 2024 5:07 PM
Class: Modern App Developement 1
Week: Week 1

# What is a design pattern?

A design pattern is a general reusable solution to a commonly occurring problem.
There are “patterns” that exist in code. Reusing these patterns can make development much faster. These patterns are meant to guide the design, not restrict it.

# MVC Paradigm

- Model
    - Core data to be stored. Including all meta data that could be used by the client.
- View
    - User side of the application.
    - Interface for user interaction. Does not need to be keyboard mouse/touch input. Take the example of google assistant that can be completely controlled by voice.
- Controller
    - Instructions sent to the system.

User uses **CONTROLLER** to manipulate the **MODEL** that updates the **VIEW** that the user sees.