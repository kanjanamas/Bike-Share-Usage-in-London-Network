# Bike-Share-Usage-in-London-Network

 เราได้เลือกชุดข้อมูลเกี่ยวกับการใช้จักรยานสาธารณะของผู้คนในเมืองลอนดอนประเทศอังกฤษจาก kaggle มาเข้ากระบวนการทาง Social Network Analysis มาใช้ในการหาศูนย์กลางของ Network นี้ สาเหตุที่เลือกข้อมูลชุดนี้ เนื่องจากคิดว่าการใช้จักรยานสาธารณะจะต้องมีจุดยืมและจุดคืน ซึ่งสามารถมองเป็นโหนดได้ มีระยะทางเข้ามาเกี่ยวข้อง สามารถตรวจจับได้ว่าบริเวณไหนอยู่ใกล้กัน จึงมองว่าเป็นการตรวจจับคอมมูนิตี้ได้รูปแบบหนึ่ง ซึ่งข้อมูลที่ได้มาจะมีข้อมูลเกี่ยวกับสถานที่ ว่ามีสถานที่ให้เช่า-คืนจักรยาน และข้อมูลการยืมคืนจักรยาน 
 
เราได้แนบ dataset มาให้ด้วยเผื่อผู้อ่านสนใจที่จะนำข้อมูลนี้ไปใช้ในการวิเคราะห์ต่อไป โดย dataset ของเรามาจาก https://www.kaggle.com/ajohrn/bikeshare-usage-in-london-and-taipei-network?select=london.csv แต่มีบางส่วนที่เรามาปรับแต่ง เช่น ใน kaggle จริงๆแล้วมีข้อมูลในส่วนของไทเปด้วย แต่เราไม่ได้นำมาใช้เนื่องจากมีการบันทึกข้อมูลป็นภาษาจีน ซึ่งผู้จัดทำไม่มีความรู้ด้านนี้ เพื่อป้องกันความผิดพลาดจึงไม่ได้นำมาใช้ในการวิเคราะห์ 

อีกทั้งยังมีขั้นตอนวิธีการทำ ตามที่ผู้จัดทำได้ทำ พร้อมกับคำสั่ง cypher ที่ใช้กับโปรแกรม Neo4j เพื่อให้ผู้อ่านได้ทราบถึงโค้ดที่ผู้จัดทำได้ใช้

รายงานนี้เป็นส่วนหนึ่งของวิชา DS535 Social Network Analysis หากมีข้อผิดพลาดประการใด ขออภัยมา ณ ที่นี้ด้วย 
ขอบคุณค่ะ :-) 
