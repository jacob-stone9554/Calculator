# Calculator

## 1. User Interface Requirements
- Display Area: A screen or display area that shows the current input and the result of calculations.
- Buttons: A grid of buttons for:
- Digits: 0-9.
- Operations: Addition (+), subtraction (-), multiplication (*), division (/).
- Special buttons: Clear (C), Equals (=), Decimal Point (.).
- Button Layout: The buttons should be laid out in a grid pattern (e.g., 4x4 for easy access).
- Responsiveness: Ensure the layout adjusts for smaller screen sizes (mobile compatibility).
 
## 2. Functionality Requirements
- Basic Arithmetic: Implement addition, subtraction, multiplication, and division.
- Clear: The "C" button should reset the current input and result.
- Decimal Support: Users should be able to enter decimal numbers, and the calculator should handle decimal arithmetic.
- Result Calculation: The "=" button should evaluate the current input and display the result.
- Input Validation: Handle invalid inputs (e.g., multiple consecutive operators or invalid characters).
- Chaining Calculations: Allow users to perform multiple calculations in sequence without pressing "C" in between (e.g., 5 + 3 = 8, 8 - 2 = 6).

## 3. Behavioral Requirements
- Input Handling: Users should be able to input numbers and operators in any order, and the calculator should respond accordingly.
- Real-time Feedback: As the user presses the buttons, the display should update immediately.
- Precedence Handling: Ensure the calculator follows standard order of operations (PEMDAS/BODMAS). For example, 2 + 3 * 4 should return 14 and not 20.
  
## 4. Edge Case Handling
- Division by Zero: Display a friendly error message when attempting to divide by zero.
- Too Long Input: Handle and limit excessively long input to prevent UI breakage or confusion.
- Floating Point Precision: Ensure that floating-point operations display correctly without rounding errors (e.g., 0.1 + 0.2 = 0.3).
