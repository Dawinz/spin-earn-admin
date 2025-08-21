# 🚀 Vercel Deployment Guide - Spin & Earn Admin

## 📋 **Step-by-Step Vercel Deployment**

### **1. Create New Vercel Project**
1. Go to [vercel.com](https://vercel.com)
2. Click "New Project"
3. Import GitHub repository: `your-username/spin-earn-admin`

### **2. Configure Project Settings**
```
Framework Preset: Create React App
Root Directory: (leave empty)
Build Command: npm run build
Output Directory: build
Install Command: npm install
```

### **3. Environment Variables**
Add this environment variable:
```
REACT_APP_API_URL=https://your-render-backend.onrender.com/api/v1
```

### **4. Deploy**
- Click "Deploy"
- Wait for build to complete
- Your admin dashboard will be available at: `https://your-project.vercel.app`

## 🎯 **After Deployment**

1. **Test Login**: Use `admin@spinearn.com` / `admin123`
2. **Verify API Connection**: Check if data loads in dashboard
3. **Test Configuration**: Try updating settings

## 🔧 **Troubleshooting**

- **Build Fails**: Check for missing dependencies
- **API Connection**: Verify `REACT_APP_API_URL` is correct
- **Login Issues**: Ensure backend is deployed and seeded

## 📝 **Notes**

- This is a standalone React app
- No complex Vercel configuration needed
- Simple deployment process
