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

column-rule-width column-rule-style column-rule-color : column�� width, ��Ÿ��, column�� �÷��� ����Ѵ�.

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

![column_rule](../images/column_rule.jpg)

## column-rule-color

�ۼ��� : �赿��

�ۼ��� : 2015-09-17

css ���۷��� ����: 
 - column-rule-color : column���� �÷��� ��� �Ѵ�.
 
 - syntax : 
```sh 
column-rule-color: color|initial|inherit;
```

column-rule-color : column �÷��� ����Ѵ�.(ex: #fff, #f3f3f3, red, rgb(255, 0, 0), rgba(255, 0, 0, 0.3), hsl(120, 100%, 50%), hsla(120, 100%, 50%, 0.3) ��)

initial:�⺻ ������ set�Ǿ� �ִ� ���� �ҷ��´�.

inherit:�θ� element�� �����Ǿ� �ִ� ���� ��� �޴´�.

sample code : 
```sh
<!DOCTYPE html>
<html>
<head>
<style> 
.newspaper {
    /* Chrome, Safari, Opera���� ����ϴ� css (�ݵ�� �տ� -webkit-�� �ٿ�����)*/
    -webkit-column-count: 3;
    -webkit-column-gap: 40px;
    -webkit-column-rule-style: outset;
    -webkit-column-rule-color: #ff0000;

    /* Firefox ���� ����ϴ� css (�ݵ�� �տ� -moz-�� �ٿ�����)*/
    -moz-column-count: 3;
    -moz-column-gap: 40px;
    -moz-column-rule-style: outset;
    -moz-column-rule-color: #ff0000;

    /*IE 10.0 ���� ���� ����ϴ� css (���� ������ ���� ����)*/
    column-count: 3;
    column-gap: 40px;
    column-rule-style: outset;
    column-rule-color: #ff0000;
}
</style>
</head>
<body>

<p><strong>Note:</strong> The column-rule-color property is not supported in Internet Explorer 9 and earlier versions.</p>

<div class="newspaper">
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum. Typi non habent claritatem insitam; est usus legentis in iis qui facit eorum claritatem. Investigationes demonstraverunt lectores legere me lius quod ii legunt saepius.
</div>

</body>
</html>

```

��� 

![column-rule-color](../images/column-rule-color.JPG)

## column-rule-style

�ۼ��� : �赿��

�ۼ��� : 2015-09-17

css ���۷��� ����: 
 - column-rule-style : column���� ��Ÿ�ϸ� ��� �Ѵ�.
 
 - syntax : 
```sh 
column-rule-style: none|hidden|dotted|dashed|solid|double|groove|ridge|inset|outset|initial|inherit;
```

none : �⺻ ��, �ƹ��͵� �������� �ʴ´�.

hidden : column�� ��Ÿ���� �����.

dotted : column�� ��Ÿ�� ª�� �������� ����

dashed : column�� ��Ÿ�� �� �������� ����

solid : column�� ��Ÿ�� ������ ����

double : column�� ��Ÿ�� �� ������ ����

groove : column�� ��Ÿ�Ͽ� groove�� �� 3D������ ����. width�� ���� ������ ����

ridge :column�� ��Ÿ�Ͽ� ridge�� �� 3D������ ����. width�� ���� ������ ����

inset : column�� ��Ÿ�Ͽ� inset�� �� 3D������ ����. width�� ���� ������ ����

outset : column�� ��Ÿ�Ͽ� outset�� �� 3D������ ����. width�� ���� ������ ����

initial:�⺻ ������ set�Ǿ� �ִ� ���� �ҷ��´�.

inherit:�θ� element�� �����Ǿ� �ִ� ���� ��� �޴´�.

sample code : 
```sh
<!DOCTYPE html>
<html>
<head>
<style> 
.newspaper {
    /* Chrome, Safari, Opera���� ����ϴ� css (�ݵ�� �տ� -webkit-�� �ٿ�����)*/
    -webkit-column-count: 3;
    -webkit-column-gap: 40px;
    -webkit-column-rule-style: dotted;

    /* Firefox ���� ����ϴ� css (�ݵ�� �տ� -moz-�� �ٿ�����)*/
    -moz-column-count: 3;
    -moz-column-gap: 40px;
    -moz-column-rule-style: dotted;

    /*IE 10.0 ���� ���� ����ϴ� css (���� ������ ���� ����)*/
    column-count: 3;
    column-gap: 40px;
    column-rule-style: dotted;
}
</style>
</head>
<body>

<p><strong>Note:</strong> The column-rule-style property is not supported in Internet Explorer 9 and earlier versions.</p>

<div class="newspaper">
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum. Typi non habent claritatem insitam; est usus legentis in iis qui facit eorum claritatem. Investigationes demonstraverunt lectores legere me lius quod ii legunt saepius.
</div>

</body>
</html>


```

��� 

![column-rule-style](../images/column-rule-style.JPG)

## column-rule-width

�ۼ��� : �赿��

�ۼ��� : 2015-09-17

css ���۷��� ����: 
 - column-rule-width : column���� ���̸� ��� �Ѵ�.
 
 - syntax : 
```sh 
column-rule-width: medium|thin|thick|length|initial|inherit;
```

medium : �⺻ ��, �߰� ũ��� �����Ѵ�.

thin : ���� ũ��� �����Ѵ�.

thick : �β��� ũ��� �����Ѵ�.

length : ���� ���� �����Ѵ�.

initial:�⺻ ������ set�Ǿ� �ִ� ���� �ҷ��´�.

inherit:�θ� element�� �����Ǿ� �ִ� ���� ��� �޴´�.

sample code : 
```sh
<!DOCTYPE html>
<html>
<head>
<style> 
.newspaper {
    /* Chrome, Safari, Opera���� ����ϴ� css (�ݵ�� �տ� -webkit-�� �ٿ�����)*/
    -webkit-column-count: 3;
    -webkit-column-gap: 40px;
    -webkit-column-rule-style: outset;
    -webkit-column-rule-width: 1px;

    /* Firefox ���� ����ϴ� css (�ݵ�� �տ� -moz-�� �ٿ�����)*/
    -moz-column-count: 3;
    -moz-column-gap: 40px;
    -moz-column-rule-style: outset;
    -moz-column-rule-width: 1px;

    /*IE 10.0 ���� ���� ����ϴ� css (���� ������ ���� ����)*/
    column-count: 3;
    column-gap: 40px;
    column-rule-style: outset;
    column-rule-width: 1px;
}
</style>
</head>
<body>

<p><strong>Note:</strong> The column-rule-style property is not supported in Internet Explorer 9 and earlier versions.</p>

<div class="newspaper">
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum. Typi non habent claritatem insitam; est usus legentis in iis qui facit eorum claritatem. Investigationes demonstraverunt lectores legere me lius quod ii legunt saepius.
</div>

</body>
</html>


```

��� 

![column-rule-width](../images/column-rule-width.JPG)

## column-span

�ۼ��� : �赿��

�ۼ��� : 2015-09-17

css ���۷��� ����: 
 - column-span : ��� column�� �����Ͽ� �ϳ��� column���� ���� �����Ѵ�.
 
 - syntax : 
```sh 
column-span: 1|all|initial|inherit;
```

1 : �⺻ ��. �ϳ��� column�� text�� �����Ѵ�.

all : ��� �÷��� �� column���� �����Ͽ� text�� �����Ѵ�.

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
    -moz-column-count: 3; /* Firefox */
    column-count: 3;
}

h2 {
    -webkit-column-span: all; /* Chrome, Safari, Opera���� ����ϴ� css (�ݵ�� �տ� -webkit-�� �ٿ�����)*/
    column-span: all; /*IE 10.0 ���� ���� ����ϴ� css (���� ������ ���� ����)*/
    /*Firefox ������ ���� ����*/
}
</style>
</head>
<body>

<p><b>Note:</b> Internet Explorer 9 (and earlier versions) and Firefox do not support the column-span property.</p>

<div class="newspaper">
<h2>Lorem ipsum dolor sit amet, consectetuer adipiscing elit</h2>
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum. Typi non habent claritatem insitam; est usus legentis in iis qui facit eorum claritatem. Investigationes demonstraverunt lectores legere me lius quod ii legunt saepius.
</div>

</body>
</html>


```

��� 

![column-span](../images/column-span.JPG)

## column-width

�ۼ��� : �赿��

�ۼ��� : 2015-09-17

css ���۷��� ����: 
 - column-width : column�� ũ�⸦ px������ �����Ѵ�.
 
 - syntax : 
```sh 
column-width: auto|length|initial|inherit;
```

auto : �⺻ ��. ������ ������� column���� �յ��ϰ� ���ҵȴ�.

length : column�� ũ�� ���� �����Ѵ�.

initial:�⺻ ������ set�Ǿ� �ִ� ���� �ҷ��´�.

inherit:�θ� element�� �����Ǿ� �ִ� ���� ��� �޴´�.

sample code : 
```sh
<!DOCTYPE html>
<html>
<head>
<style> 
.newspaper {
    -webkit-column-width: 100px; /* Chrome, Safari, Opera���� ����ϴ� css (�ݵ�� �տ� -webkit-�� �ٿ�����)*/
    -moz-column-width: 100px; /* Firefox ���� ����ϴ� css (�ݵ�� �տ� -moz-�� �ٿ�����)*/
    column-width: 100px; /*IE 10.0 ���� ���� ����ϴ� css (���� ������ ���� ����)*/
}

</style>
</head>
<body>

<p><b>Note:</b> Internet Explorer 9 (and earlier versions) and Firefox do not support the column-span property.</p>

<div class="newspaper">
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum. Typi non habent claritatem insitam; est usus legentis in iis qui facit eorum claritatem. Investigationes demonstraverunt lectores legere me lius quod ii legunt saepius.
</div>

</body>
</html>


```

��� 

![column-width](../images/column-width.JPG)

## columns

�ۼ��� : �赿��

�ۼ��� : 2015-09-17

css ���۷��� ����: 
 - columns : column�� ���� �� ũ�⸦ �����Ѵ�.
 
 - syntax : 
```sh 
columns: auto|column-width column-count|initial|inherit;
```

auto : �⺻ ��. ������ ������� column���� �յ��ϰ� ���ҵȴ�.

column-width column-count : column�� ũ�� ���� ������ �����Ѵ�.

initial:�⺻ ������ set�Ǿ� �ִ� ���� �ҷ��´�.

inherit:�θ� element�� �����Ǿ� �ִ� ���� ��� �޴´�.

sample code : 
```sh
<!DOCTYPE html>
<html>
<head>
<style> 
.newspaper {
    -webkit-columns: 100px 3; /* Chrome, Safari, Opera���� ����ϴ� css (�ݵ�� �տ� -webkit-�� �ٿ�����)*/
    -moz-columns: 100px 3; /* Firefox ���� ����ϴ� css (�ݵ�� �տ� -moz-�� �ٿ�����)*/
    column-columns: 100px 3; /*IE 10.0 ���� ���� ����ϴ� css (���� ������ ���� ����)*/
}

</style>
</head>
<body>

<p><b>Note:</b> Internet Explorer 9 (and earlier versions) and Firefox do not support the column-span property.</p>

<div class="newspaper">
Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer possim assum. Typi non habent claritatem insitam; est usus legentis in iis qui facit eorum claritatem. Investigationes demonstraverunt lectores legere me lius quod ii legunt saepius.
</div>

</body>
</html>


```

��� 

![columns](../images/columns.JPG)