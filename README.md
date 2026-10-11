# K2 - CafeIN Manajemen Coffe Shop
# PROJEK Software Development
# Daftar Anggota
1. Bima Abidzar
2. Yusuf Kurniawan
3. Azka Zulfa
# DESKRIPSI SINGKAT PROJEK CafeIN
CafeIN adalah Aplikasi/Website yang berfokus pada otomatisasi rekap data operasional dan perhitungan pendapatan bulanan secara akurat, sehingga pemilik kafe dapat memantau performa keuangan bisnis mereka secara real-time tanpa perlu pencatatan manual.


# Road Map Projek
```mermaid
+------------------------------------------------------------------------+
|                   PUBLIC & AUTHENTICATION                              |
+------------------------------------------------------------------------+
|                                                                        |
|  [Landing Page] --> [Register] --> [Login] --> [JWT Session]           |
|                                                   |                    |
+---------------------------------------------------|--------------------+
                                                    |
                                                    v
                                      +-------------------------+
                                      |   ROLE-BASED ACCESS     |
                                      |         (RBAC)          |
                                      +-------------------------+
                                                    |
                         +--------------------------+----------------------+
                         |                                                 |
                         v                                                 v
          +---------------------------+                     +---------------------------+
          |     LEADER WORKSPACE      |                     |      MEMBER WORKSPACE     |
          +---------------------------+                     +---------------------------+
          |                           |                     |                           |
          | 1. Dashboard              |                     | 1. My Tasks               |
          |    - Total Task           |                     |    - Assigned Task        |
          |    - Completed            |                     |    - In Progress          |
          |    - Overdue              |                     |    - Completed             |
          |    - Progress Divisi      |                     |                           |
          |                           |                     | 2. Task Detail            |
          | 2. Project Management     |                     |    - Description          |
          |    - CRUD Project         |                     |    - Deadline              |
          |    - CRUD Task            |                     |    - Priority              |
          |    - Status & Priority    |                     |    - Update Status         |
          |                           |                     |    - Upload Attachment     |
          | 3. Delegasi Tugas         |                     |    - Comment               |
          |    - Ke Divisi            |                     |                           |
          |    - Ke Anggota           |                     | 3. Activity History        |
          |                           |                     |    - Task History          |
          | 4. Manajemen Organisasi   |                     |                           |
          |    - Divisi               |                     |                           |
          |    - Anggota              |                     |                           |
          +---------------------------+                     +---------------------------+
                         |                                                 |
                         +--------------------------+----------------------+
                                                    |
                                                    v
+------------------------------------------------------------------------+
|                     CROSS-CUTTING SERVICES                              |
+------------------------------------------------------------------------+
|                                                                        |
|  - Client & Server Validation      - Search / Filter / Pagination      |
|  - Toast & Error Handling          - JWT & RBAC                        |
|  - Cloud Storage                   - Activity / Task History           |
|  - Analytics & Data Aggregation                                         |
|                                                                        |
+------------------------------------------------------------------------+
                                                    |
                                                    v
+------------------------------------------------------------------------+
|                       DATABASE & STORAGE                                |
+------------------------------------------------------------------------+
|                                                                        |
|  - User & Role Data                                                    |
|  - Project Data                                                        |
|  - Task Data                                                           |
|  - Division & Member Data                                              |
|  - Comments & Attachments                                              |
|  - Activity History                                                    |
|                                                                        |
+------------------------------------------------------------------------+
```
