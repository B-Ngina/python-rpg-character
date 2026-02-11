# python-rpg-character
A terminal-based character generator focused on input validation and dynamic UI rendering. It ensures game balance by enforcing strict data entry rules before generating a visual stat sheet.

Key Features

The "Rule of 7": A validation gate that ensures the sum of Strength, Intelligence, and Charisma equals exactly 7.

Guard Clauses: Prevents errors by checking for data types (integers), name length (<10 chars), and no spaces.

Visual Progress Bars: Uses string multiplication to convert raw integers into a 10-dot visual scale (●●●○○○○○○○).

Technical Skills

Logic: Multi-condition if statements for game-balance enforcement.

Validation: Type-checking using isinstance().

Formatting: Clean string concatenation for terminal UI.
