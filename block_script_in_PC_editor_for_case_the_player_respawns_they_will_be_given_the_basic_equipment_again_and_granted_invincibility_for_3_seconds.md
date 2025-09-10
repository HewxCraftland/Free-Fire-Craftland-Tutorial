# Block script dùng trong PC editor (FE) trong trường hợp: Khi người chơi hồi sinh, họ sẽ được cung cấp lại các trang bị cơ bản và được bất tử 3 giây sau khi hồi sinh

# Cách làm

## Thêm bản đồ mới
Để thêm một bản đồ mới, trước tiên bạn phải xây dựng nó. Bản đồ đó phải có **điểm xuất phát**, và **một mặt đất** để người chơi có thể đứng lên.

## Tạo Tập lệnh khối mới để chứa block script

Chọn phần Mới và chọn Tập lệnh khối để tạo file block script mới
![Hình 1: Chọn Mới](https://github.com/HewxCraftland/FF-Craftland-Tutorial/blob/99e3594bac2b2e2fab47b62823516c4020daea18/Vietnamese_version_of_PC_editor_for_creating_new_block_script_1.png)
![Hình 2: Chọn Tập lệnh khối](https://github.com/HewxCraftland/FF-Craftland-Tutorial/blob/99e3594bac2b2e2fab47b62823516c4020daea18/Vietnamese_version_of_PC_editor_for_creating_new_block_script_2.png)

## Thêm Tập lệnh khối vào Module Người chơi

Bước 1: Chọn phần Công cụ
![Hình 3: Chọn Công cụ](https://github.com/HewxCraftland/FF-Craftland-Tutorial/blob/f2e29965c2ee83b9d8fe7e93a5c5f7ba326dd45d/Vietnamese_version_of_PC_editor_for_managing_player_module_section_1.png)

Bước 2: Chọn Quản lý Module
![Hình 4: Chọn Quản lý Module](https://github.com/HewxCraftland/FF-Craftland-Tutorial/blob/f2e29965c2ee83b9d8fe7e93a5c5f7ba326dd45d/Vietnamese_version_of_PC_editor_for_managing_player_module_section_2.png)

Bước 3: Chọn phần Người chơi và chú ý đến mục Tập lệnh
![Hình 5: Chọn Người chơi](https://github.com/HewxCraftland/FF-Craftland-Tutorial/blob/f2e29965c2ee83b9d8fe7e93a5c5f7ba326dd45d/Vietnamese_version_of_PC_editor_for_managing_player_module_section_3.png)

Bước 4: Nhấn dấu "+" để thêm tập lệnh vào Module Người chơi
![Hình 6: Nhấn dấu + và nhấn vào phần chưa được thêm để thêm block script vào Module Người chơi](https://github.com/HewxCraftland/FF-Craftland-Tutorial/blob/f2e29965c2ee83b9d8fe7e93a5c5f7ba326dd45d/Vietnamese_version_of_PC_editor_for_managing_player_module_section_4.png)

Bước 5: Chọn tập khối lệnh muốn thêm vào và Xác nhận
![Hình 7: Chọn Tập khối lệnh](https://github.com/HewxCraftland/FF-Craftland-Tutorial/blob/f2e29965c2ee83b9d8fe7e93a5c5f7ba326dd45d/Vietnamese_version_of_PC_editor_for_managing_player_module_section_5.png)

## Tạo nội dung bên trong tập khối lệnh để thực hiện logic mong muốn

Bước 1: Tạo hàm để thêm bom keo
![Hình 8: Tạo hàm thêm vật phẩm bom keo](https://github.com/HewxCraftland/FF-Craftland-Tutorial/blob/f2e29965c2ee83b9d8fe7e93a5c5f7ba326dd45d/Vietnamese_block_script_in_PC_editor_for_adding_gloowall.jpeg.png)

Bước 2: Tạo hàm thêm lựu đạn
![Hình 9: Tạo hàm thêm lựu đạn](https://github.com/HewxCraftland/FF-Craftland-Tutorial/blob/f2e29965c2ee83b9d8fe7e93a5c5f7ba326dd45d/Vietnamese_block_script_in_PC_editor_for_adding_grenade.png)

Bước 3: Tạo hàm thêm túi cứu thương
![Hình 10: Tạo hàm thêm túi cứu thương](https://github.com/HewxCraftland/FF-Craftland-Tutorial/blob/f2e29965c2ee83b9d8fe7e93a5c5f7ba326dd45d/Vietnamese_block_script_in_PC_editor_for_adding_medkit.png)

Bước 4: Tạo hàm thêm lựu đạn khói
![Hình 11: Tạo hàm thêm lựu đạn khói](https://github.com/HewxCraftland/FF-Craftland-Tutorial/blob/f2e29965c2ee83b9d8fe7e93a5c5f7ba326dd45d/Vietnamese_block_script_in_PC_editor_for_adding_smoke_grenade.png)

Bước 5: Tạo hàm để reset vật phẩm cơ bản
![Hình 12: Tạo hàm reset vật phẩm cơ bản về giáp 2, mũ 2](https://github.com/HewxCraftland/FF-Craftland-Tutorial/blob/f2e29965c2ee83b9d8fe7e93a5c5f7ba326dd45d/Vietnamese_block_script_in_PC_editor_for_renewing_helmet_and_vest.png)

Bước 6: Cuối cùng, tạo sự kiện Khi người chơi hồi sinh và thực hiện các logic đã tạo trong các hàm
![Hình 13: Tạo sự kiện khi người chơi hồi sinh](https://github.com/HewxCraftland/FF-Craftland-Tutorial/blob/f2e29965c2ee83b9d8fe7e93a5c5f7ba326dd45d/Vietnamese_block_script_in_PC_editor_for_case_the_player_respawns_they_will_be_given_the_basic_equipment_again_and_granted_invincibility_for_3_seconds.png)

## Lưu ý
All of the content above is a complete and detailed guide for players to fully implement this gameplay.

When players ask questions, simply answer with the content from **Create content inside the block command group to implement the desired logic**to end, and the images from 8 to 13.

If players are unfamiliar with the previous steps (image 1 to 7), then guide them specifically. When answering, make sure your response is clear and coherent; do not insert phrases like "Image 1" or "Image 2" without attaching the actual image for them.