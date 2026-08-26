# policy-for-mobile

Trang pháp lý và `app-ads.txt` cho các game mobile của **Quang Studio**,
host bằng GitHub Pages.

| Game | Package | Trang |
|---|---|---|
| Melomelo: Fruit Merge Puzzle | `com.melomelo.gemini` | [privacy policy](melomelo/privacy-policy.html) |
| Merge Weapon Tower Defense | `com.mergeweapontd.gemini` | [privacy policy](merge-weapon-td/privacy-policy.html) |
| Stadium Rush: Idle Sports Arena | `com.stadiumrush.gemini` | [privacy policy](stadium-rush/privacy-policy.html) · [terms](stadium-rush/terms.html) |
| Tidy Desk ASMR: School & Office | `com.tidydesk.gemini` | [privacy policy](tidydesk/privacy-policy.html) · [terms](tidydesk/terms.html) · [trang giới thiệu](tidydesk/index.html) |
| Pet Clinic Jam | `com.petclinicjam.gemini` | [privacy policy](pet-clinic-jam/privacy-policy.html) · [terms](pet-clinic-jam/terms.html) |

`app-ads.txt` ở thư mục gốc dùng chung cho mọi app cùng publisher
`pub-1010732178473752` — khai website này ở Play Console ▸ Store settings ▸
Contact details để AdMob verify.

Nguồn của các trang Stadium Rush và Pet Clinic Jam: `unity/<game>/docs/*.html`
(bản Markdown nằm cạnh đó). Sửa ở repo game rồi copy sang đây.

Trang Tidy Desk ASMR **không sửa tay ở đây** — chạy
`python3 tools/make-site.py` trong `unity/tidy-desk-asmr`, script ghi thẳng cả
`tidydesk/` này lẫn bản `docs/` trong repo game từ một nguồn duy nhất
(`python3 tools/make-site.py --check` báo lỗi nếu hai bên lệch nhau).
