---
title: 'Policy of life'
date: 2025-06-20
permalink: /posts/2025/04/policy-of-life/
author_profile: false
related: false
tags:
  - nonsense
---
Cuộc đời của mỗi con người, nếu nhìn qua lăng kính của AI, đặc biệt là Reinforcement Learning, chính là một hành trình học hỏi không ngừng, nơi ta đóng vai **agent** trong một môi trường rộng lớn, phức tạp và đầy bất định.

Khi chúng ta chào đời, ta giống như một agent mới tinh, không có nhiều kiến thức về thế giới xung quanh. Môi trường (**environment**) mà ta đối mặt là cuộc sống, nơi mọi thứ diễn ra không theo một kịch bản cố định. Không ai hướng dẫn chi tiết cho ta rằng nên sống thế nào để đạt được hạnh phúc hay thành công. Do đó, ta phải tự mình tương tác với môi trường, thử nghiệm các hành động (**actions**), và dần dần khám phá ra quy luật vận hành của thế giới này. 

Mỗi ngày trôi qua, ta đưa ra vô số quyết định – từ những lựa chọn nhỏ bé như ăn gì sáng nay, đến những quyết định lớn lao như chọn ngành nghề, bạn đời hay lối sống. Mỗi hành động đó đều dẫn đến một trạng thái mới (**new state**) và nhận về một phần thưởng (**reward**) – có thể là tích cực (reward > 0), hoặc tiêu cực (reward < 0). Chính những phần thưởng này giúp ta update **policy** (chuỗi các hành động) để dần dần học cách hành động tốt hơn trong tương lai.

Nhưng giống như trong RL, không phải lúc nào phần thưởng cũng đến ngay sau hành động. Nhiều khi, ta chấp nhận những khó khăn trước mắt để nhận được giá trị lâu dài hơn, **Delayed Reward**, vốn là thử thách lớn nhất không chỉ trong thuật toán mà cả trong cuộc sống con người.

Ví dụ, khi ta quyết định học hành chăm chỉ trong nhiều năm, đó là một chuỗi hành động mà không có phần thưởng ngay lập tức. Nhưng về lâu dài, nó có thể mang lại cơ hội nghề nghiệp tốt, thu nhập cao và sự ổn định, một **cumulative reward** đáng giá.

## Đánh đổi - expoitation and exploration
Một trong những vấn đề trong RL là sự cân bằng giữa Exploration (Khám phá) và Exploitation (Khai thác). Và đây cũng chính là điều mà con người phải đối mặt mỗi ngày.

* Nếu ta chỉ tập trung vào khai thác những gì đã biết (exploitation), cuộc sống sẽ trở nên an toàn nhưng dễ nhàm chán, và ta có thể bỏ lỡ những cơ hội tiềm ẩn.

* Ngược lại, nếu ta quá mải mê khám phá (exploration), không ngừng thử những điều mới mẻ mà không xây dựng nền tảng vững chắc, ta có thể rơi vào trạng thái bất ổn, thiếu định hướng.

Nếu coi hạnh phúc là reward, thì một agent khôn ngoan là người biết khi nào nên bước ra khỏi vùng an toàn để khám phá, và khi nào nên tận dụng những gì đã học được để tối ưu hóa giá trị đó.

## Học cách thích nghi trong Non-stationary environment
Trong thực tế, môi trường sống của chúng ta không bao giờ là stationary. Nó luôn thay đổi theo thời gian, từ sự thay đổi của xã hội, công nghệ, đến những biến động trong bản thân ta như sức khỏe, tâm lý hay các mối quan hệ. Đây chính là thách thức của Non-stationary environment trong RL, khi mà những policy cũ không còn phù hợp, buộc ta phải liên tục học lại, cập nhật bản thân để thích nghi.