# terraform_begin
## Задание 1.
3. 

![ключ_значения_random_password](https://github.com/user-attachments/assets/f7196b05-bc04-4a62-9bd6-002825ab5ce5)

4.

   ![спец_ошибка](https://github.com/user-attachments/assets/38a3b9da-33a8-4402-9283-834310922dc6)
   - Отсутствует имя блока resource
   - Имя ресурса должно начинаться либо с буквы, либо с нижнего подчеркевания
   - В блоке random_password файла state-файла нет ключа "random_string_FAKE", а также resulT. есть только "random_string" и "result"

5. 
   
![docker_ps](https://github.com/user-attachments/assets/7e412938-c2b3-48ad-96a4-d72d204c0c31)
  
5. Команда "terraform apply -auto-approve" применяет без подтверждения. Опасность даннного ключа заключается в том что при его применении не проверяется что будет изменено, таким образом можно применить ошибочные изменения. Данный ключ полезен когда есть 100% уверенность в правильном исполнении команды, а так же при рализации IaaC.

![image](https://github.com/user-attachments/assets/8db2d5aa-cb8c-4550-a5fe-fc1a632f6d28)
7.  
![image](https://github.com/user-attachments/assets/a62aac8a-3a87-4f1c-bbf9-46f24208952b)

8. Образ небыл удален из-за того что ключ keep_locally в main.tf имеет значение True
![image](https://github.com/user-attachments/assets/87087ed4-8020-4f57-bdc6-e75bab3fb63c)
 https://docs.comcloud.xyz/providers/kreuzwerker/docker/latest/docs/resources/image#:~:text=keep_locally%20(Boolean)%20If%20true%2C%20then%20the%20Docker%20image%20won%27t%20be%20deleted%20on%20destroy%20operation.%20If%20this%20is%20false%2C%20it%20will%20delete%20the%20image%20from%20the%20docker%20local%20storage%20on%20destroy%20operation.



