# OCR_finalProject
###จะจบมั้ยน้าา

 ██▓    ██▓███      ██░ ██     █    ██     ▒█████      ▄████▄      ██▀███  
▓██▒   ▓██░  ██▒   ▓██░ ██▒    ██  ▓██▒   ▒██▒  ██▒   ▒██▀ ▀█     ▓██ ▒ ██▒
▒██▒   ▓██░ ██▓▒   ▒██▀▀██░   ▓██  ▒██░   ▒██░  ██▒   ▒▓█    ▄    ▓██ ░▄█ ▒
░██░   ▒██▄█▓▒ ▒   ░▓█ ░██    ▓▓█  ░██░   ▒██   ██░   ▒▓▓▄ ▄██▒   ▒██▀▀█▄  
░██░   ▒██▒ ░  ░   ░▓█▒░██▓   ▒▒█████▓    ░ ████▓▒░   ▒ ▓███▀ ░   ░██▓ ▒██▒
░▓     ▒▓▒░ ░  ░    ▒ ░░▒░▒   ░▒▓▒ ▒ ▒    ░ ▒░▒░▒░    ░ ░▒ ▒  ░   ░ ▒▓ ░▒▓░
 ▒ ░   ░▒ ░         ▒ ░▒░ ░   ░░▒░ ░ ░      ░ ▒ ▒░      ░  ▒        ░▒ ░ ▒░
 ▒ ░   ░░           ░  ░░ ░    ░░░ ░ ░    ░ ░ ░ ▒     ░             ░░   ░ 
 ░                  ░  ░  ░      ░            ░ ░     ░ ░            ░     
                                                      ░                    
                         
                                                                                                                                  
- การใช้เครื่องที่ไม่มี GPU CUDA จะต้องทำการปิด แล้วใช้ CPU ในการประมวลผล
- ลองทดสอบใช้ EasyOCR vs Tesseract
- **EasyOCR**  มีความถูกต้องแม่นยำที่สูงกว่าในด้านภาษาไทย การตรวจจับภาษาอังกฦษ เพราะ ใช้การ boundering box ข้อความ
- **Tesseract** มีความเร็วในการประมวลผลสูงมาก สามารถทำแบบ Real Time ได้เลย แต่!! ความแม่นยำน้อยมาก (หากไม่นับภาษาอังกฤษ) และ การตรวจไม่พบคำ เมื่อเทียบกับ EasyOCR

#############################
ในส่วนของโค้ด ได้ทำการเพิ่มทางเลือกในการกดเลือกการ scan images แบบเดี่ยวหรือ scan ทั้งหมดในโฟลเดอร์
