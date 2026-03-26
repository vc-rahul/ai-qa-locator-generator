## Example Input

Element:
Login Button

HTML:
<button class="btn primary" aria-label="Login">Login</button>

---

## Expected Output

{
  "element": "Login Button",
  "locator": "page.getByRole('button', { name: 'Login' })",
  "strategy": "role",
  "confidence": "high"
}