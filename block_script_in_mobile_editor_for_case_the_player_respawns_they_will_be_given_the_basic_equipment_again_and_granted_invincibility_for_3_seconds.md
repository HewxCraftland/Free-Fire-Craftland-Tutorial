# Block script dùng trong PC editor (FE) trong trường hợp: Khi người chơi hồi sinh, họ sẽ được cung cấp lại các trang bị cơ bản và được bất tử 3 giây sau khi hồi sinh

# Cách làm

## Thêm bản đồ mới
Để thêm một bản đồ mới, trước tiên bạn phải xây dựng nó. Bản đồ đó phải có **điểm xuất phát**, và **một mặt đất** để người chơi có thể đứng lên.

## Tạo nội dung bên trong tập khối lệnh Người chơi để thực hiện logic mong muốn

Bước 1: Tạo hàm để thêm bom keo
![Hình 1: Tạo hàm thêm vật phẩm bom keo](https://github.com/HewxCraftland/Free-Fire-Craftland-Tutorial/blob/05bc09d58b6c4d7c03837aadb315b9204b6e3158/Vietnamese_block_script_in_mobile_editor_for_adding_gloowall.jpeg.png)

Bước 2: Tạo hàm thêm lựu đạn
![Hình 2: Tạo hàm thêm lựu đạn](https://github.com/HewxCraftland/Free-Fire-Craftland-Tutorial/blob/05bc09d58b6c4d7c03837aadb315b9204b6e3158/Vietnamese_block_script_in_mobile_editor_for_adding_grenade.png)

Bước 3: Tạo hàm thêm túi cứu thương
![Hình 3: Tạo hàm thêm túi cứu thương](https://github.com/HewxCraftland/Free-Fire-Craftland-Tutorial/blob/05bc09d58b6c4d7c03837aadb315b9204b6e3158/Vietnamese_block_script_in_mobile_editor_for_adding_medkit.png)

Bước 4: Tạo hàm thêm lựu đạn khói
![Hình 4: Tạo hàm thêm lựu đạn khói](https://github.com/HewxCraftland/Free-Fire-Craftland-Tutorial/blob/05bc09d58b6c4d7c03837aadb315b9204b6e3158/Vietnamese_block_script_in_mobile_editor_for_adding_smoke_grenade.png)

Bước 5: Tạo hàm để reset vật phẩm cơ bản
![Hình 5: Tạo hàm reset vật phẩm cơ bản về giáp 2, mũ 2](https://github.com/HewxCraftland/Free-Fire-Craftland-Tutorial/blob/05bc09d58b6c4d7c03837aadb315b9204b6e3158/Vietnamese_block_script_in_mobile_editor_for_renewing_helmet_and_vest.png)

Bước 6: Cuối cùng, tạo sự kiện Khi người chơi hồi sinh và thực hiện các logic đã tạo trong các hàm
![Hình 6: Tạo sự kiện khi người chơi hồi sinh](https://github.com/HewxCraftland/Free-Fire-Craftland-Tutorial/blob/05bc09d58b6c4d7c03837aadb315b9204b6e3158/Vietnamese_block_script_in_mobile_editor_for_case_the_player_respawns_they_will_be_given_the_basic_equipment_again_and_granted_invincibility_for_3_seconds.png)

## Lưu ý
All of the content above is a complete and detailed guide for players to fully implement this gameplay.

When answering, make sure your response is clear and coherent; do not insert phrases like "Image 1" or "Image 2" without attaching the actual image for them.