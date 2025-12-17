# Vercel Test1.lua Deployment

Project này để deploy file Test1.lua lên Vercel.

## Cách deploy:

### Cách 1: Sử dụng Vercel CLI

1. Cài đặt Vercel CLI (nếu chưa có):
```bash
npm i -g vercel
```

2. Đăng nhập vào Vercel:
```bash
vercel login
```

3. Deploy project:
```bash
cd vercel_test1
vercel
```

4. Để deploy production:
```bash
vercel --prod
```

### Cách 2: Deploy qua GitHub

1. Tạo repository trên GitHub
2. Push code lên GitHub
3. Vào [vercel.com](https://vercel.com)
4. Import project từ GitHub
5. Vercel sẽ tự động detect và deploy

## Sau khi deploy:

File sẽ có thể truy cập qua:
- `https://your-domain.vercel.app/api/test1`
- `https://your-domain.vercel.app/test1.lua`

Bạn có thể sử dụng URL này trong Roblox script như:
```lua
loadstring(game:HttpGet("https://your-domain.vercel.app/api/test1"))()
```

