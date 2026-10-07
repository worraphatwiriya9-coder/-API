# Product Explorer — API + React Hook Form + Zod

โปรเจกต์นี้จัดไว้สำหรับงาน Web Technology ที่เน้น 3 ส่วนหลัก:

- External API ด้วย `https://dummyjson.com`
- React Hook Form
- Zod สำหรับ Schema และ Validation

## โครงสร้างหลัก

- `app/lib/products.ts` — Zod Schema, Type และฟังก์ชันเรียก External API
- `app/components/ProductExplorer.tsx` — ศูนย์กลาง State และการโหลดข้อมูล
- `app/components/ProductSearchForm.tsx` — ฟอร์มค้นหา + React Hook Form + Zod
- `app/components/ProductForm.tsx` — ฟอร์มเพิ่ม/แก้ไขสินค้า + React Hook Form + Zod
- `app/data/products-fallback.json` — ข้อมูลสำรองเมื่อเรียก API ไม่สำเร็จ
- `app/page.tsx` — หน้าแรกที่เรียกใช้ ProductExplorer

## รันโปรเจกต์

```bash
npm install
npm run dev
```

จากนั้นเปิด `http://localhost:3000`
