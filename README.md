# Rock-Paper-Scissors

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rock Paper Scissors Game</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    
    <h1>Rock Paper Scissors</h1>
    <div class="choices">
      <div class="choice" id="rock">
        <img src="data:image/jpeg;base64,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" />
      </div>
      <div class="choice" id="paper">
        <img src="data:image/jpeg;base64,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" />
      </div>
      <div class="choice" id="scissors">
        <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxAQEhUQEBIQFhUWFRUVEhISEhUVEBIQFRIWFxUVFRUYHiggGBolHRUVITEhJSkrLi4uFx8zODMsNygtLisBCgoKDQ0NDg0QDisZFRkrKysrKystLS0tKzcrNysrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrK//AABEIAOEA4QMBIgACEQEDEQH/xAAcAAACAgMBAQAAAAAAAAAAAAACAwEEAAcIBgX/xABGEAABAwEGAwUECAMECgMAAAABAAIDEQQSEyExUQVBYQYHInGBFDKRoQgjQnKCorHwUmKSQ7KzwSQ1U2NzdIOTwtEVFzP/xAAVAQEBAAAAAAAAAAAAAAAAAAAAAf/EABURAQEAAAAAAAAAAAAAAAAAAAAR/9oADAMBAAIRAxEAPwDcifZ9PVZgDqocbmQ+aBkuhVVNEhdluiwB1QHFoEFp0CEyFuQ5KWm/kfkgSrqTgDqhxzsEEWjX0Qw+8Exrb+Z+SkxhuY5IHKpLqUeOdgiEQOeeaAbNqU8pLhczHzUY52CBSsWfT1UYA6qHOuZD5oDm0KqpwkLsiiwB1QMj0Hkl2nkhxSMtlLTf15bIEhXUnBHVDjnYIItGvoog94fvkja29mfkpLLuYQOVOTU+aZjnYIhEDnnnmgGzc092iS4XNOe6jGJyoEClifgDcqUoLFbulSi8cs0pPs+nqgBjCDU6J2K3dZLoVVQMewk1AUxC7rkmxaBBadB5oDxW7qvhu2Qq6gTEbooclMjgRQapdo19EMOoQZhO2T2PAFCUxVJdSgbKb2maVhnZHZtSnlAOK3dKlF41GaUrFn09UC42kGp0TsVu6ibQqsgNzCTUBHF4dck2PQeSXaeSAzIN1XwnbIQrqBMbg0UOSmRwIoNUu0a+iiH3h++SCMN2ye14AoSmKnJqfNA2U3tM0AjOyKzc092iAcVu4WKopVFrCbsEqXwmgyRY42Khwv5j5qAWOJNCU7CbsEoRlueyLHGxQA9xBoCpiN455rDGXZ7qQLmZ+SBmGNgq+Idym442KHAO4QFELwqc1MjQBUBCHXMj55LDJeyHNAvEO5Xmu0feFwqwOw7RODKPeiiaZJGnZ13Jpz0JC+b3wdqH8MsX1LqTzuw4nDVgpV8g6gUAPIuC5kjjfK+jQ973HIAFz3uJ5DUkoOpeCd53CbY4RxWgRvJADZmmIuJyADj4STtWq9biHcri62WSWF5jmjkjePeZI1zHjza7MLfXcV2xktbHWC0vLpIWh8L3Gr3wVoWuJ1LSW0Ox6INv4bdglSm6aDJFjjYpNrmY1jpnuaxjGlz3ONGta0Vc4nkAEBscSaHROw27Bc4duO+C12iR0fD3OggBIEjRS0SjMXi7+zB5AUPVeRsHbvi0LxIy3WskcpJnyMPmx5IPwQdbOeQaAo4vFrmtf91vb9vF2OimDGWqMXntbkyWPIYjAcxmRUcqjdbAb4NeeyBhjGwVfEO5TccbFDgHcICiaCKnNTI0AVCEOu5FYZL2QQLxDuU9rARUhLwDuEQlAy2yQRKLumSWHncpjjf05bqMEjPJA3DbsFiD2gbFYgRRPs+nqnKvaNfRA2XQqqii1CtoAi0CC0aBKl1KOz6+iBVFcqsKpoG2jX0QRahOs+nqpm0KDSP0mI3f6C/7I9ob0Djgn5gfJeJ7k5I28XgvipLZmxk/ZkwXkH4Aj1W1+/fh4l4W6TnBLG/yDnYR/vhaD7KcT9ktlntNaCOaNzj/ACXhf/LVBt/6RHCA6Gz2xrfE17oXuAzLHtvMvHoWup94rXndFxL2fi1lcTQPcYndcVpaB/UWrfXfJw72jhNoA1YGzN/6bg535b65asNpMUjJW6se1482uBH6IOz1rfv6406DhzbOx1HWiUMdnQ4LG3n/ABNweRK2dYrQ2WNkrdHta8eTgCP1XO30huLYvEGWcEFsEIBG0shvu/LhoPAdmeDvt1qhskZoZXht46Nbq51OjQT6LYHev3c2ThdlhtFmfMSZGwyCVzTfLmPcHigFD4CKdQj+jtwrEt0tpI8MMJAP+9lIA/K1/wAl9j6SXF/FZbEDoHTvHnWOP9JEGvu6e3Pg4tZHMJ8coicORZKCwg/EH0C6utHJcvdyvC/aOKxO5QtfO7zaLrPzOb8F1BZuaBQVyqwqkgbPr6KIfeH75Jtn09VM2h/fNAdVVk1PmgVyPQeSBNn5p7jklWnkkN1QQpV1Ygr456KWi/mfkl4Ttk2I3cjkgwxhuYrkgxz0THvBFBqk4TtkDWxh2eeahwuZj5omPAFColN7TNAOOeiPAHVJwnbJ+K3dADnXMh81AkLsjzWSC8ajNQxhBqUHzO13CBabFaYMyZIZAPvXat9agLjhdwYrd1xv2w4Z7JbrTZwKCOZ4aNmXqs/KQg6k7MWgcR4ZCX0pNZQ19M/EWGN/wIcuSLVA6J7o3ijmOc1w2c00I+IXR30f+JCThmGT/wDjNIz0eRIP77vgtNd6/DvZ+K2pgFGukxW7EStD8vVxHog3/wB1HFsbhNlcaeCPCcdsFxYPytC5p7W8VNsttotJNRJM9zf+HeowejQ0ei2B3fdpfZuB8SZeo6M/V55g2pgiFPItJ+K1XFGXODWipJAA3JNAEHSHcJwgwcMM7h4p5XPGX9m0CNo+IefxLTne1xj2vitpcDVsb8BnlF4T+YOPqujWlnC+FU1FlslTyLnxRVPq5w+a5Gnlc9znuNXOJc47uJqSg3r9HDgwwbTbHVq97YWn+VgD3U8y5v8AStxuFzTnuvMd13DRY+F2WIijnRiV4Ot+Xxmv9QHovTym9pmgjGPRHgDqlCN2yfit3QLc67kPmoa+9kVkgLjUZqI2kGp0QMwB1QGUjLLJNxW7pDoyTUBAbTf15bIjCBnmhi8OuSMyjdAvHPRYgwnbLFRbVe0a+iDEO5TYhUZ5qBUWoVtLewAVASMQ7lBkupR2fX0TGMBFSEMwu6ZIGlU0WIdyrGG3YIBs+nqvh9t+1Vn4XZjaJ6mpuxxtNHyya3RtuTyC8p2z73rDYJHQQtdaJWEh7Y3BkTHjVpkINT90HbVaX7xe3MnGZYpHRYTYmFrY8TE8TnVc69dbrRopT7KD6XF++Hi8zy6KVkDOUcUbHZdXvaST8PJeM41xaa2TOtNodflfdvvutbeusDAaNAFaNGgXq+63sEOMyTB8xijha0uLWhz3OkvBoFTQDwkk56U5r5HbrsnLwm1GzSOvigdFKG3WyRnnSpoQQQRXltRB7/6OnEbs1qsxPvxslaOsbi009JB8Ej6RHD7lqs9oH9rC5h+9E/8A9SNXmu53iGBxazEnwyF0Tq6ESMIA/qurbX0heGCThzJwM4Z2k/ckBYfncQc7R2p7WOia4hjy0vbycWVu18rx+K9P3V8J9q4pZmEVax+M/wC7F48+hIaPVeSW5vo8WCOM2viEzmNYxrYQ97g1gvEPfUnL7LPj1Qer79uLGDhuE0+K0Ssj/wCm0F7z+Vo/EtBdl+Fm12yz2YAnFmjY6n8BcL59G1Povcd+Xayz2+0wx2SRskULHVe2oaZ3u8QFR4gGtZmMsyqvcdgN4m2SeSNhbG/BvuDb0zqMDWk5Vuueg6ULQMhoMh5DIJtm5pjGAjMIJvDSmSBxVJGHndWMMbBANn09VM2h/fNLlNDQZKI3EmhQLVuPQeSjDGwSHPINAUDLTySG6p0Oda5phjGwQGsVTEO5UIGYB3CkG5kfNOqkWjX0QEZL2W6HAO4QRahWqoFCS7lsoJv5BLl1KOz6oMwDuF47vc7SusPDZXxEtkkLYI3Vza6QG8R1DWvXuCVqL6Q3+rof+bZ/gToNA2OyvmkZFE0ue9waxo1c5xoAF9rtV2Lt/DLhtkN1r/ce1zXxlwFS0uacndD6Kh2b4qbHaoLUBXClY8t/iDXZj4VXVHbLhEXGOGvjjIdixtls7/8AeAB0Z9dD0JQaB7mu0/sHEGB5pFP9TLsCT9W70dQeTitsd+vZn2qwG1sH1llJeNzA6glB8qB34TuubpGFpLXAggkOBFCCDQgjkVs6198tpl4c+wyQNdK+PCdab+RYRQuMdPfplrSpr0Qa34da3QSxzN96N7JG/eY4OH6LpHvS7WcMfw6ezS2iPEmiBiiacR+Jk+O8GVu5gZmi5lRRsc4hrQSTkABUk9AEApmM67h3nXalwZU3A8gAuu6VoAK9Avcdmu6Xitso50Qs8Z+3aPC6nSP3ifMDzW0ez3ctw+zUdaS+1PyNHeCAHoxpqfUnyQaA4Xwa02oltmgmlI1wo3Op5kDL1SLZZJIXmOZj2Pb7zJGlrweoOYXZnDrJHCGxxMZGwaMY0NYMuQGS1n9IfgLJLGy3NaMSGRrHv5mB9RQ70eWU+8UFfuK7eyWgO4danFz42XrPI41c6JtA6Nx5luRB2rstuk39MqLkHsHxP2XiNln5NmYHf8N5uP8AyuK6+s/NBGAd0XtA2TSVTogcW38wsDLuaKDT1UzaH980A442KHCJz3zSqK3Gch5IFAXNc6qcYHKiy0ckkBAzAO4WJ9VKCkn2fT1U4A6oXG5kPmgZLoVVTRIXZHmjwB1QFFoEFp0HmhMhbkOSlpv5H5IErW30jv8AVsP/ADjP8CdbRwB1WqvpDku4bF0tcZP/AGZx/mg52W7e5/vKstnswsVvkMeEXGGRwc5rojV1wkVIINadCByWneE8PfaZo7PFS/I8MZeNG3nGgqeSs8U7PW2yvMdos08bh/FG6h6hwycOoKB/bTiMNqt1ptEApHJK5zARQkH7VOVTU+qry8CtDbKy3Fn1D5DE19RnI0VIpqBkc+i+x2T7AW/iMgayJ8cdRfnlY5sTW86V985aDpWmq6LtvYOyS8NHCwHNjawCN4pfbKHXsTq4uJJ3vFBy12ebZTaIhbXSNs97650QrIG0Og86V50quhezfaPsrYWVsklmjNPfMcmOfNz23/RaY7T92/E7A8h9nfLHXKaBrpIyNzQVZ+IBeYdYZgaGOSu1x1f0QdEcX75uFRA4JmndyDIyxlerpKfIFeHg79beJw50NnwL2cIDr9zmBIT71OdKdFqxkDy4Rhri8kNDKG8XE0Dab15LbPZLuStD3Nk4k5sUeTsCN16Z4/hc4ZMHkSfJBvuG0NlibKz3Xsa9v3XAEfIrzvb+xibhtsjIr/o8rmj+aNhe35tC9DAAAIwAGgBoA5NAyA+Cq9oYWiy2iv8AsJvhhOQcZLsvg1qM1ks0p1fDE8+bo2k/quM12B2EF7h1jB5WaD/Cag+sFdSsEdUvHPRBlo19FEHvD98kxrb2Z+SxzA3MIHKnJqfNHjnojEQOeeaAbNzT3aJLhc057ocYnLJAqixWcAdVionGbulyC9mElWLPp6qAGsINTom4rd1MuhVRA1zCTUKYxdzKbFoEFp0HmgLFbutb9+tlLuEyOp7ksLvzFv8A5L36+L3l2A2jhdsjAqcBz2jUl0fjAHXw09UHLHZS0YVtsslaXbRCSdgJG1+S7IlIcKariMGmYXZXZ63C0wQWgaSRMf6uYCfnVBewnbJrZABQpqqS6lA2Q3vdXwO2XFhw+xz2twFY2G5XnK7wxj+ohfds2pWpfpIcULLNZrKK/WyPkdtdiaAAfWQH0QeZ7iOz/tdsk4laKuEJq0uFb9rkqbxPMtFT5uaV0BILxqF4juj4SLNwqzigvStM7zzJlzaT+AMHovdWfT1QLYwg1Oi+P28tgj4bbX1oRZZwD/M6JzW/Mhfdm0K1t34cUwOFvYD4p5GRAfy1L3Hyoyn4gg5pXZnZmz4Nls8bsrsELfVsTQVyL2c4ebTaoLOBXEmjYR0c8A/Kq7KnFAAP3kgMyjdJwnbIArqBMbg0UKl7wRQapdo19FEPvD98kGYTtk1sgAoU1U5NT5oGyG9ogEZ2RWbmnu0QBjN3WKqpQW8NuwSZsjll5IvaOigi/nogCNxJoSrGGNglYV3PZT7R0QLe4gkAoocznn5qcK9nXVZS5nqgZhjYKrJ4gWuqQQQRuDkU/H6IcDqg437S8LdY7XPZnCmFK9o6sr4HeraH1W/u4bjotHDjZifrLK4t/mwZCXMPlW+38K8t9ITssWvj4lGKhwEVooMg4Vw3nzHhr/K3da+7ve1buF2xs+ZjcLk7B9qInMgfxAgEeXVB1hfO5VhjAQCQFTsE0dojZNDI18b2hzHtza5pVkS3cqaIJmFNMvJfI41wOy20Nba4Y5Qw3mYgrdPOh1z5jmvrE38tFmB1QHHAxoDWtaAAAAAAAAKAAcglzGhoMvJF7R0UFt/PTkgGNxJoVzr399pG2m2iyROBjswLXU0NpcfrP6QGt6EOWyu9LvAi4XG6CB7XWt7SGNGeAHAjEfsRybzy5Lmo35H/AGnve7q573uPxJJPzQbH7heCGfiBtJHgszC4HljSAsYPgXn8K6Qhz1z815Luw7If/G2FkTqYsn1s/OkjgPB5NAA86nmvWgXOtUDDGNgq2IdynY/RD7P1QFEKjPPzUyNAFRkhD7mWqwyXskCr53KsMYCBUBLwDuixqZU0yQRMKUpl5JYedymE3+lFGDTOqB2GNgoQe0dCsQIon2fT1TlXtGvogbKciqtEUWoVtAERyCC0aBKl1KOza+iBVFcqsKpIFcc4dFaon2eZt6ORhY9u4Ox5EZEHkQFyp277Hz8KtBikBMbqmCanhlZ/k4VAI/yIXXNn09VR7RcFs9tgdBao2yRnkci13JzXDNrhuEHMXYHvFtfCTdZ9bATV9neSBXm6N2dx3oQdlvbsn3jcP4m4RxPcyZwJEEouvNASbhHhfkCaA1pyWqO13cza7OTJYD7RHrcJDbQwbUJo/wAxn0Xyu7jsbxGTiNndgTxNhlZJLLJG5jWsY68RV1Kk0u0H8WyDp6z6p5KVadAkBBV4rb2WaGS0S1DImOe+gqbrRWgG509Vz/2k76OI2gOjswZZozzZ4p6dZDkMqe6Aeq6K4zw2O1QS2aWtyVjo3UNDRwpUHfn6LR3/ANCTCUh1tiEVcnCJxlLa/wAFQAfxINPuc+V9Tee97tTVz3vcfiSSVvTui7sn2Ytt9vZSXWzwEZxV0kk/n2by1OeQ9n2L7vOH8NcHxRl8v+3lN54y+yNGegr1Xt0ARnIeSC0ckmTU+aZZuaBYCt1CwqkgbPqoh1/eybZ9PVTPof3zQHUKq8ZnzQK5HoPJAmz805xyS7TySG6oMWK6sQVsc9ETBezKDBdt+iZGbuRQY6MNzHJBjnomPeCKDVKwXbfogY2MHM81DxczHzRMeAKFDIb2QQDjHomYA6pWE7ZOxW7oAe67kFDZC7I81kgvZhQxhBqdEDMAdUDpCMhyTMVu6U6Mk1GiAmG/kfkiwR1Qxi7qjxW7oFY56ImNvZlBhO2/RMjddFCgxzA3MIMc9Ex7wRQapWC7b9EDGxA5nmoeLmnPdE2QAUPJDJ4tEA4x6JmAOqUInbJ2M3dAtzruQWNeXZFZI0uNQoYwtNTogZgDqgMpGQpkmYzd0p0ZJqEBMN/XlsiMIGeaGMXfeRmUboFY56LEOC7b5rEFtV7Rr6Jd87lOhFRnn5oFRahW0uRoAqAq987lBMupR2fX0TI2ggEhDMKaZeSBpVNFfO5Vm4NggCz6eqKbQpUxocsvJDG4kgEoAVqLQKbg2CrvcQSAUDLToEgJsOeufmnFg2CAlWtGvogvncp0IqM8/NAuHUK0lStAFQkXzuUEyanzTLNzRsaCBUBDPlSmXkgaVSRh53Ks3BsEAWfT1Uz6H980uY0OWXkoiJJoUC1bj0HksuDYKu9xBOZQMtPJIbqnQ51rn5pjmDYIDWKnfO5WIGez9VINzLVOvBInzOWyCcS9lTVR7P1QxjMKzeG4QJEt3Kmiwm/logkGZRQZHNBmB1RY/RNLgqd07FA4tv56clmHdz2RQZD1UynIoBx+ijCrnXVJunYq1GcggWBcz1U4/RZPnokgHYoGez9VIdcy15p1QkT5nLZBJkvZUUYHVDEMwrN4bhAkS0yposJv9KJbxmfNMgyrVBGB1Re0dEwkKpdOxQOLb+eiwMu56ooDkpmOSAPaOizCrnXXNJunYq0w5DyQLAudaqcauVFlozpRJAOxQM9n6rE+8FiCkrFm0UrFQU3ulVFixQW4tAgtOg8/8lixBXCvLFiCtadfRDDqFixUW1Tl1KxYoDs2pVgqViCgrVm09VixUTP7pVVYsUFyLQeSVaeSlYgrhXlixBWtGvohg94LFiC2qcmp81CxA2y8092hWLEFFYsWKj//2Q==" />
      </div>
    </div>

    <div class="score-board">
      <div class="score">
        <p id="user-score">0</p>
        <p>You</p>
      </div>
      <div class="score">
        <p id="comp-score">0</p>
        <p>Comp</p>
      </div>
    </div>

    <div class="msg-container">
      <p id="msg">Play your move</p>
    </div>
    <script src="app.js"></script>
</body>
</html>