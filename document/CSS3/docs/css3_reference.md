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

![column-rule-color](../images/column-rule-color.jpg)

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

![column-rule-style](../images/column-rule-style.jpg)

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

![column-rule-width](../images/column-rule-width.jpg)

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

![column-span](../images/column-span.jpg)

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

![column-width](../images/column-width.jpg)

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

![columns](../images/columns.jpg)

## @keyframes

�ۼ��� : �赿��

�ۼ��� : 2015-09-18

css ���۷��� ����: 
 - @keyframes : �ܰ������� ��ȭ�� �ִ� �ִϸ��̼� �ڵ�
 
 - syntax : 
```sh 
@keyframes animationname {keyframes-selector {css-styles;}}
```

animationname : ����� �ִϸ��̼� ���� �����Ѵ�.

keyframes-selector : �ִϸ��̼��� %���� �����Ѵ�.

                     ���� ���� 0 ~ 100% �Ǵ� from(0%) ~ to(100%)

css-styles : �ϳ� �̻��� css ��Ÿ���� �����Ѵ�.

sample code : 
```sh
<!DOCTYPE html>
<html>
<head>
<style> 
div {
    width: 100px;
    height: 100px;
    background: red;
    position :relative;
    -webkit-animation: mymove 5s infinite; /* Chrome, Safari, Opera */ 
    animation: mymove 5s infinite;
}

/* Chrome, Safari, Opera */ 
@-webkit-keyframes mymove1 {
    0%   {top: 0px;}
    25%  {top: 200px;}
    75%  {top: 50px}
    100% {top: 100px;}
}

/* Standard syntax */
@keyframes mymove {
    0%   {top: 0px;}
    25%  {top: 200px;}
    75%  {top: 50px}
    100% {top: 100px;}
}
</style>
</head>
<body>

<p><strong>Note:</strong> The @keyframes rule is not supported in Internet Explorer 9 and earlier versions.</p>

<div></div>

</body>
</html>

```

��� 

[http://www.w3schools.com/cssref/tryit.asp?filename=trycss3_keyframes](http://www.w3schools.com/cssref/tryit.asp?filename=trycss3_keyframes)

## border-image

�ۼ��� : �赿��

�ۼ��� : 2015-09-18

css ���۷��� ����: 
 - border-image : border�� �̹����� �����Ѵ�.
 
 - syntax : 
```sh 
border-image: source slice width outset repeat|initial|inherit;
```

source slice width outset repeat : border�� ����ϴ� �̹��� ���, slice Ÿ��, ũ��(%), outset, �ݺ�(round/stretch) ���� �����Ѵ�.

initial:�⺻ ������ set�Ǿ� �ִ� ���� �ҷ��´�.

inherit:�θ� element�� �����Ǿ� �ִ� ���� ��� �޴´�.

sample code : 
```sh
<!DOCTYPE html>
<html>
<head>
<style> 
#borderimg1 { 
    border: 10px solid transparent;
    padding: 15px;
    -webkit-border-image: url(border.png) 30 round repeat; /* Safari 3.1-5 */
    -o-border-image: url(border.png) 30 round; /* Opera 11-12.1 */
    border-image: url(border.png) 30 round; /*ie11 and chrome �������� ���*/
}

#borderimg2 { 
    border: 10px solid transparent;
    padding: 15px;
    -webkit-border-image: url(border.png) 30 stretch; /* Safari 3.1-5 */
    -o-border-image: url(border.png) 30 stretch; /* Opera 11-12.1 */
    border-image: url(border.png) 30 stretch; /*ie11 and chrome �������� ���*/
}
</style>
</head>
<body>

<p>The border-image property specifies an image to be used as the border around an element:</p>
<p id="borderimg1">Here, the middle sections of the image are repeated to create the border.</p>
<p id="borderimg2">Here, the middle sections of the image are stretched to create the border.</p>

<p>Here is the original image:</p><img src="border.png">
<p><strong>Note:</strong> Internet Explorer 10, and earlier versions, do not support the border-image property.</p>

</body>
</html>

```

��� 

![border-image](../images/border-image.jpg)

## border-image-outset

�ۼ��� : �赿��

�ۼ��� : 2015-09-18

css ���۷��� ����: 
 - border-image-outset : border image�� ���� ũ���� �����Ѵ�.
 
 - syntax : 
```sh 
border-image-outset: length|number|initial|inherit;
```

length : ǥ���� ���� �����Ѵ�. �⺻���� 0�̸�, ǥ�� �� px������ �����Ѵ�.

number : border ũ���� ����� ǥ���Ѵ�.

initial:�⺻ ������ set�Ǿ� �ִ� ���� �ҷ��´�.

inherit:�θ� element�� �����Ǿ� �ִ� ���� ��� �޴´�.

sample code : 
```sh
<!DOCTYPE html>
<html>
<head>
<style> 
div {
    /*ie11,chrome */
    border: 15px solid transparent;
    padding: 5px;   
    border-image: url(border.png);
    border-image-slice: 30;
    border-image-repeat: round;
    border-image-outset:0 0 0 0;
    
    /*Safari 3.1-5*/
    -webkit-border-image: url(border.png);
    -webkit-border-image-slice: 30;
    -webkit-border-image-repeat: round;
    -webkit-border-image-outset:0 0 0 0;

    /*Opera 11-12.1*/
    -o-border-image: url(border.png);
    -o-border-image-slice: 30;
    -o-border-image-repeat: round;
    -o-border-image-outset:0 0 0 0;
    }
</style>
</head>
<body>

<div>
This DIV uses an image as a border.
</div>
<p>Here is the image used:</p>
<img src="border.png">

<p><b>Note: </b>Internet Explorer 10, Opera 12, and Safari 5 do not support the border-image-repeat property.</p>

</body>
</html>


```

��� 

![border-image-outset](../images/border-image-outset.jpg)

## border-image-repeat

�ۼ��� : �赿��

�ۼ��� : 2015-09-18

css ���۷��� ����: 
 - border-image-repeat : border image�� �ݺ� Ÿ���� �����Ѵ�.
 
 - syntax : 
```sh 
border-image-repeat: stretch|repeat|round|initial|inherit;
```

stretch :�⺻ ��, �̹����� full�� ä���.

repeat : �̹����� �ٵ��ǽ����� �ݺ������� ä���.

round : �̹����� �ٵ��ǽ����� �ݺ������� ä���. �̹��� ��ü�� ä���� ���ϴ� ��� �̹����� ������ ũ��� ���ġ�Ѵ�.

initial:�⺻ ������ set�Ǿ� �ִ� ���� �ҷ��´�.

inherit:�θ� element�� �����Ǿ� �ִ� ���� ��� �޴´�.

sample code : 
```sh
<!DOCTYPE html>
<html>
<head>
<style> 
div {
    /*ie11,chrome */
    border: 15px solid transparent;
    padding: 5px;   
    border-image: url(border.png);
    border-image-slice: 30;
    border-image-repeat: repeat;
    border-image-outset:0 0 0 0;
    
    /*Safari 3.1-5*/
    -webkit-border-image: url(border.png);
    -webkit-border-image-slice: 30;
    -webkit-border-image-repeat: repeat;
    -webkit-border-image-outset:0 0 0 0;

    /*Opera 11-12.1*/
    -o-border-image: url(border.png);
    -o-border-image-slice: 30;
    -o-border-image-repeat: repeat;
    -o-border-image-outset:0 0 0 0;
    }
</style>
</head>
<body>

<div>
This DIV uses an image as a border.
</div>
<p>Here is the image used:</p>
<img src="border.png">

<p><b>Note: </b>Internet Explorer 10, Opera 12, and Safari 5 do not support the border-image-repeat property.</p>

</body>
</html>


```

��� 

![border-image-repeat](../images/border-image-repeat.jpg)

## border-image-slice

�ۼ��� : �赿��

�ۼ��� : 2015-09-18

css ���۷��� ����: 
 - border-image-slice : border image�� �ڸ��� ������ �����Ѵ�.
 
 - syntax : 
```sh 
border-image-slice: number|%|fill|initial|inherit;
```

number : �ڸ� �̹����� px ������ ������ �����Ѵ�.

% : �ڸ� �̹����� ũ�⳪ ���̸� %������ �����Ѵ�.

fill : �ڸ��� �̹������� ��ü�� �����ش�.

initial:�⺻ ������ set�Ǿ� �ִ� ���� �ҷ��´�.

inherit:�θ� element�� �����Ǿ� �ִ� ���� ��� �޴´�.

sample code : 
```sh
<!DOCTYPE html>
<html>
<head>
<style>
#borderimg1 {
    border: 10px solid transparent;
    padding: 15px;
    -webkit-border-image: url(border.png) round; /* Safari 3.1-5 */
    -o-border-image: url(border.png) round; /* Opera 11-12.1 */
    border-image: url(border.png) round;
    border-image-slice: 50;
}

#borderimg2 {
    border: 10px solid transparent;
    padding: 15px;
    -webkit-border-image: url(border.png) round; /* Safari 3.1-5 */
    -o-border-image: url(border.png) round; /* Opera 11-12.1 */
    border-image: url(border.png) round;
    border-image-slice: 20%;
}

#borderimg3 {
    border: 10px solid transparent;
    padding: 15px;
    -webkit-border-image: url(border.png) round; /* Safari 3.1-5 */
    -o-border-image: url(border.png) round; /* Opera 11-12.1 */
    border-image: url(border.png) round;
    border-image-slice: 30%;
}
</style>
</head>
<body>

<p id="borderimg1">border-image-slice: 50;</p>
<p id="borderimg2">border-image-slice: 20%;</p>
<p id="borderimg3">border-image-slice: 30%;</p>

<p>Here is the image used:</p>
<img src="border.png">

<p><strong>Note:</strong> Internet Explorer 10, and earlier versions, do not support the border-image-slice property.</p>

</body>
</html>

```

��� 

![border-image-slice](../images/border-image-slice.jpg)

## border-image-source

�ۼ��� : �赿��

�ۼ��� : 2015-09-18

css ���۷��� ����: 
 - border-image-source : border image�� ��θ� �����Ѵ�.
 
 - syntax : 
```sh 
border-image-source: none|image|initial|inherit;
```

none : �̹����� ������� �ʴ´�.

image : �̹��� ��θ� �����Ѵ�.

initial:�⺻ ������ set�Ǿ� �ִ� ���� �ҷ��´�.

inherit:�θ� element�� �����Ǿ� �ִ� ���� ��� �޴´�.

sample code : 
```sh
<!DOCTYPE html>
<html>
<head>
<style> 
#borderimg { 
    border: 10px solid transparent;
    padding: 15px;
    border-image-source: url(border.png);    
    border-image-slice: 30;
}
</style>
</head>
<body>

<p>The border-image-source property specifies the image to be used as the border around an element:</p>
<p id="borderimg">Hello World!</p>

<p>Here is the original image:</p><img src="border.png">
<p><strong>Note:</strong> Internet Explorer 10, and earlier versions, do not support the border-image-source property.</p>

</body>
</html>

```

��� 

![border-image-source](../images/border-image-source.jpg)

## border-image-width

�ۼ��� : �赿��

�ۼ��� : 2015-09-18

css ���۷��� ����: 
 - border-image-width : border image�� ũ�⸦ �����Ѵ�.
 
 - syntax : 
```sh 
border-image-width: number|%|auto|initial|inherit;
```

number : �̹��� ũ�⸦ px ������ �����Ѵ�

% : �̹��� ũ�⸦ % ������ �����Ѵ�.

auto : �ڸ� �̹����� ���ǵǾ� �ִ� ũ�� �Ǵ� ���̿� ���� �ڵ������� ���ǵȴ�.

initial:�⺻ ������ set�Ǿ� �ִ� ���� �ҷ��´�.

inherit:�θ� element�� �����Ǿ� �ִ� ���� ��� �޴´�.

sample code : 
```sh
<!DOCTYPE html>
<html>
<head>
<style> 
#borderimg1 { 
    border: 10px solid transparent;
    padding: 15px;
    border-image-source: url(border.png);
    border-image-repeat: round;
    border-image-slice: 30;
    border-image-width: 10px;        
}

#borderimg2 { 
    border: 10px solid transparent;
    padding: 15px;
    border-image-source: url(border.png);
    border-image-repeat: round;
    border-image-slice: 30;
    border-image-width: 20px;        
}

#borderimg3 { 
    border: 10px solid transparent;
    padding: 15px;
    border-image-source: url(border.png);
    border-image-repeat: round;    
    border-image-slice: 30;
    border-image-width: 30px;        
}
</style>
</head>
<body>

<p>The border-image-width property specifies the width of the border image:</p>
<p id="borderimg1">border-image-width: 10px;</p>
<p id="borderimg2">border-image-width: 20px;</p>
<p id="borderimg3">border-image-width: 30px;</p>

<p>Here is the original image:</p><img src="border.png">
<p><strong>Note:</strong> Internet Explorer 10, and earlier versions, do not support the border-image-width property.</p>

</body>
</html>

```

��� 

![border-image-width](../images/border-image-width.jpg)

## backface-visibility

�ۼ��� : �赿��

�ۼ��� : 2015-09-18

css ���۷��� ����: 
 - backface-visibility : div �ױ� �޸��� ��� ���θ� �����Ѵ�.
 
 - syntax : 
```sh 
backface-visibility: visible|hidden|initial|inherit;
```

visible : �⺻ ��, �޸��� ��������.

hidden : �޸��� �����.

initial:�⺻ ������ set�Ǿ� �ִ� ���� �ҷ��´�.

inherit:�θ� element�� �����Ǿ� �ִ� ���� ��� �޴´�.

sample code : 
```sh
<!DOCTYPE html>
<html>
<head>
<style>
div {
    position: relative;
    height: 60px;
    width: 60px;
    background-color: red;
    -webkit-transform: rotateY(180deg);  /* Chrome, Safari, Opera */
    transform: rotateY(180deg);
}

#div1 {
    -webkit-backface-visibility: hidden;  /* Chrome, Safari, Opera */
    backface-visibility: hidden;
}

#div2 {
    -webkit-backface-visibility: visible;  /* Chrome, Safari, Opera */
    backface-visibility: visible;
}
</style>
</head>
<body>

<p>This example shows two div elements, rotated 180 degrees, facing away from the user.</p>
<p>The first div element has the backface-visibility property set to "hidden", and should therefore be invisible.</p>

<div id="div1">DIV 1</div>
<div id="div2">DIV 2</div>

<p><strong>Note:</strong> The backface-visibility property is not supported in Internet Explorer 9 and earlier versions.</p>

</body>
</html>


```

��� 

![backface-visibility](../images/backface-visibility.jpg)