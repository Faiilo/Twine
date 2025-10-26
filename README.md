# Twine
1. Добавление раздела [[Дальше]]
2. Добавление картинки персонажа <img src = "https://github.com/Z1Dipex/Twine/blob/main/kandinsky-download-1761045140574-no-bg-preview%20(carve.photos).png?raw=true](https://github.com/Faiilo/Twine/blob/main/task_01k8fx7mfke24agvxzcq7w1m1n_1761470635_img_0-edited-free%20(carve.photos).png?raw=true)">
```
<img src = "https://github.com/Z1Dipex/Twine/blob/main/kandinsky-download-1761045140574-no-bg-preview%20(carve.photos).png?raw=true">
```
3. Добавление фона 
```
tw-story {
  background-image: url('https://github.com/Z1Dipex/Twine/blob/main/image.png?raw=true');
    background-size: cover
}
```
4. Добавление подложки у текста
```
<div class="text-box">
    Дмитрий мечтал заниматься современным делом, связанным с технологиями. Узнав о курсах МДКд.12.01, он решил освоить профессию цифрового куратора, помогающего другим людям овладевать цифровыми инструментами. Но впереди его ждут испытания: справится ли он с учебой и какими новыми возможностями откроются перед ним?
    [[Дальше]]
</div>
```
```
#.passage {
    position: relative;
}
#
.text-box {
    background-color: rgba(0, 0, 0, 0.7);
    color: white;
    padding: 10px;
    border-radius: 10px;
    margin-top: 10px;
    position: fixed;
    bottom: 20px;
