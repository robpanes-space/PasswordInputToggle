# PasswordInputToggle
React and tailwind component that displays password input and can be toggled as input to view the value

# Usage

```
<PasswordInputToggle
        ref={pwdRef}
        inputValue={formData.shop_api_password}
        inputLabel="Api Secret (optional)"
        inputName="shop_api_password"
        onChange={(e) => onChangeInput(e)}
        tooltip={{
          enabled: true,
          message: `Optional but we may need it sometime in the future, but we encourage you to add it now so we may not ask
        you in the near future.`,
        }}
      />
```
