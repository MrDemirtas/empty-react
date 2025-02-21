# 🚀 React + Vite Başlangıç Şablonu

Bu şablon, React ve Vite kullanarak hızlı bir şekilde yeni bir proje başlatmanız için hazırlanmıştır.

## 📋 Başlarken

### Kurulum

1. Şablonu klonlayın:

Mevcut dizine klonlama:
```bash
git clone https://github.com/MrDemirtas/empty-react.git .
```

Varsayılan klasör adıyla klonlama:
```bash
git clone https://github.com/MrDemirtas/empty-react.git
```

Özel bir klasör adıyla klonlama:
```bash
git clone https://github.com/MrDemirtas/empty-react.git my-react-app
```

2. Proje klasörüne gidin (mevcut dizine klonladıysanız bu adımı atlayın):

Varsayılan klasör için:
```bash
cd empty-react
```

Özel klasör için:
```bash
cd my-react-app
```

3. Bağımlılıkları yükleyin:

npm ile:
```bash
npm install
```

## ⚠️ Önemli Yapılacaklar

Projeye başlamadan önce aşağıdaki adımları tamamlayın:

1. Aşağıdaki terminal kodlarından size uygununu çalıştırarak dosyaları silin ve Git geçmişini temizleyin:

Windows PowerShell için:
```powershell
Remove-Item "README.md","public\delete_this_file",".git" -Recurse -Force; git init
```

Windows CMD için:
```bash
del README.md && del public\delete_this_file && rmdir /s /q .git && git init
```

Bash için:
```bash
rm README.md public/delete_this_file && rm -rf .git && git init
```

Not: Windows'ta `rm -rf` komutu çalışmaz. Bash kullanmıyorsanız PowerShell veya CMD komutlarını kullanın.

2. `package.json` dosyasını düzenleyin:
```json
{
  "name": "your-project-name"
}
```

Not: Proje adı küçük harflerden oluşmalı ve tire (-) ile ayrılmalıdır. Örnek: "my-awesome-project"

## 🚀 Geliştirme

Geliştirme sunucusunu başlatmak için:

```bash
npm run dev
```

## 📦 Dağıtım

Projeyi derlemek için:

```bash
npm run build
```

## 🛠️ Kullanılan Teknolojiler

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)