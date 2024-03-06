temporary configure.yml file save :
development:
  password: 
  theme_id: "3e7d91-32"
  store: raccoons.myshopify.com
  proxy: http://localhost:3000
  ignore_files:
    - "*.gif"
    - "*.jpg"
    - config/settings_data.json
production:
  password: 
  theme_id: "3e7d91-32"
  store: raccoons.myshopify.com
  timeout: 60s
  readonly: true
test:
  password: 
  theme_id: "3e7d91-32"
  store: raccoons.myshopify.com
  ignores: .env
