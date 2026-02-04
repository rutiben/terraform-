mkdir learn-terraform-docker-container – יצירת ספריית עבודה חדשה עבור הפרויקט.

cd learn-terraform-docker-container – כניסה לתוך ספריית העבודה שנוצרה.

touch main.tf – יצירת הקובץ הראשי שבו מגדירים את המשאבים.

terraform init – -Docker אתחול התיקייה והורדת ספק ה

terraform fmt - פורמט הקוד .

terraform validate – לוודא שאין שגיאות תחביר בקוד.

terraform plan – הצגת תוכנית ביצוע כדי לוודא שהפריסה תואמת למצב הרצוי.

terraform apply –   ויצירת הקונטיינר על פורט 8000, Image  יצירת התשתית בפועל, משיכת ה-

                                                                                                                                                            עריכת קובץ main.tf – החלפת ערך הפורט החיצוני מ-8000 ל-8001 בתוך הקוד

                                                                                                                                                    מזהה את שינוי הפורט, מחריב את הקונטיינר הישן ויוצר חדש במקומו   terraform apply  –                                 
terraform state list –Terraform  בדיקת רשימת המשאבים המנוהלים על ידי 

terraform destroy – (הקונטיינר וה-Image)  שנוצרו החרבת התשתית ומחיקת כל המשאבים 
