# templates_the_band_2
---khi merge
	/backend/controller/__pycache__
	/backend/models/__pycache__
	/backend/router/__pycache__

---push code mình lên trước
		git add .
		git commit -m"update lần 1"
		git push

---bắt đầu chuyển nhánh master
		git checkout master 
		git pull  (pull code về)
---Xong rồi chuyển lại về nhánh mình và merge sang nhánh master
		git checkout Phu
		git merge master (nếu merge ko đc thì thêm origin kế bên master như vầy nà git merge origin/master )

---xong coi lựa code xóa mấy head đi, sau khi merge xong thì push code lên nhánh của mình
		git add .
		git commit -m"update lần 2"
		git push