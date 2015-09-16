# CSS3 Reference

## column-count

�ۼ��� : �赿��

�ۼ��� : 2015-09-14

css ���۷��� ����: 
 - column-count : div �� �ؽ�Ʈ�� �����Ѵ�.

 - syntax : 
```sh 
column-count: length|auto|initial|inherit;
```

length:column ������ ����Ѵ�.

auto:�⺻ ��, column-width�� ���� �÷� ���� �����ȴ�.

initial:�⺻ ������ set�Ǿ� �ִ� ���� �ҷ��´�.

inherit:�θ� element�� �����Ǿ� �ִ� ���� ��� �޴´�.

sample code : 
```sh
<!DOCTYPE html>
<html>
<head>
<style> 
.newspaper {
    -webkit-column-count: 3; /* Chrome, Safari, Opera���� ����ϴ� css (�ݵ�� �տ� -webkit-�� �ٿ�����)*/
    -moz-column-count: 3; /* Firefox���� ����ϴ� css (�ݵ�� �տ� -moz-�� �ٿ�����)*/
    column-count: 3; /*IE 10.0 ���� ���� ����ϴ� css (���� ������ ���� ����)*/
}
</style>
</head>
<body>

<p><strong>Note:</strong> The column-count property is not supported in Internet Explorer 9 and earlier versions.</p>

<div class="newspaper">
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum. Typi non habent claritatem insitam; est usus legentis in iis qui facit eorum claritatem. Investigationes demonstraverunt lectores legere me lius quod ii legunt saepius.
</div>

</body>
</html>
```

��� 

![column_count](../images/column-count.JPG)


## column-gap

�ۼ��� : �赿��

�ۼ��� : 2015-09-14

css ���۷��� ����: 
 - column-gap : column���� ���ҵ� �ؽ�Ʈ ������ ������ �����Ѵ�.
 
 - syntax : 
```sh 
column-gap: length|normal|initial|inherit;
```

length:column ũ�⸦ ����Ѵ�.(px,em ��)

normal:�⺻ ��, W3C������ 1em�� ���� ��õ�Ѵ�. 

initial:�⺻ ������ set�Ǿ� �ִ� ���� �ҷ��´�.

inherit:�θ� element�� �����Ǿ� �ִ� ���� ��� �޴´�.

sample code : 
```sh
<!DOCTYPE html>
<html>
<head>
<style> 
.newspaper {
    -webkit-column-count: 3; /* Chrome, Safari, Opera���� ����ϴ� css (�ݵ�� �տ� -webkit-�� �ٿ�����)*/
    -moz-column-count: 3; /* Firefox���� ����ϴ� css (�ݵ�� �տ� -moz-�� �ٿ�����)*/
    column-count: 3; /*IE 10.0 ���� ���� ����ϴ� css (���� ������ ���� ����)*/

    -webkit-column-gap: 40px; /* Chrome, Safari, Opera���� ����ϴ� css (�ݵ�� �տ� -webkit-�� �ٿ�����)*/
    -moz-column-gap: 40px; /* Firefox ���� ����ϴ� css (�ݵ�� �տ� -moz-�� �ٿ�����)*/
    column-gap: 40px; /*IE 10.0 ���� ���� ����ϴ� css (���� ������ ���� ����)*/
}
</style>
</head>
<body>

<p><strong>Note:</strong> The column-count property is not supported in Internet Explorer 9 and earlier versions.</p>

<div class="newspaper">
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum. Typi non habent claritatem insitam; est usus legentis in iis qui facit eorum claritatem. Investigationes demonstraverunt lectores legere me lius quod ii legunt saepius.
</div>

</body>
</html>
```

��� 

![column_gap](../images/column-gap.JPG)

## column-rule

�ۼ��� : �赿��

�ۼ��� : 2015-09-14

css ���۷��� ����: 
 - column-rule : column���� width, style ���� ��� �Ѵ�.
 
 - syntax : 
```sh 
column-rule: column-rule-width column-rule-style column-rule-color|initial|inherit;
```

column-rule-width column-rule-style column-rule-color : column�� width, ��Ÿ��, �÷��� ����Ѵ�.

initial:�⺻ ������ set�Ǿ� �ִ� ���� �ҷ��´�.

inherit:�θ� element�� �����Ǿ� �ִ� ���� ��� �޴´�.

sample code : 
```sh
<!DOCTYPE html>
<html>
<head>
<style> 
.newspaper {
    -webkit-column-count: 3; /* Chrome, Safari, Opera���� ����ϴ� css (�ݵ�� �տ� -webkit-�� �ٿ�����)*/
    -moz-column-count: 3; /* Firefox���� ����ϴ� css (�ݵ�� �տ� -moz-�� �ٿ�����)*/
    column-count: 3; /*IE 10.0 ���� ���� ����ϴ� css (���� ������ ���� ����)*/

    -webkit-column-gap: 40px; /* Chrome, Safari, Opera���� ����ϴ� css (�ݵ�� �տ� -webkit-�� �ٿ�����)*/
    -moz-column-gap: 40px; /* Firefox ���� ����ϴ� css (�ݵ�� �տ� -moz-�� �ٿ�����)*/
    column-gap: 40px; /*IE 10.0 ���� ���� ����ϴ� css (���� ������ ���� ����)*/

    -webkit-column-rule: 4px outset #ff00ff; /* Chrome, Safari, Opera ���� ����ϴ� css (�ݵ�� �տ� -webkit-�� �ٿ�����)*/
    -moz-column-rule: 4px outset #ff00ff; /* Firefox css ���� ����ϴ� css (�ݵ�� �տ� -moz-�� �ٿ�����)*/
    column-rule: 4px outset #ff00ff; /*IE 10.0 ���� ���� ����ϴ� css (���� ������ ���� ����)*/
}
</style>
</head>
<body>

<p><strong>Note:</strong> The column-count property is not supported in Internet Explorer 9 and earlier versions.</p>

<div class="newspaper">
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum. Typi non habent claritatem insitam; est usus legentis in iis qui facit eorum claritatem. Investigationes demonstraverunt lectores legere me lius quod ii legunt saepius.
</div>

</body>
</html>
```

��� 

![column_gap](../images/column-rule.jpg)
