angular js mvc partten 
���� : Model / View / Controller �� ���ڷ� software achitecher partten �� �ϳ��� ���� ���
Ư¡ : 
- �ϳ��� ����� ���ȭ�Ͽ� ������ �� ���뼺�� ����
- �Ҽ��� �پ �����Ͼ���� �ذ��� ������ �ټ��� �����Ͼ���� ó���� �� �ֵ��� �����ν�, �����ڵ鰣�� Ŀ�´����̼� ȿ�뼺�� ����
  (ex �ʿ伺..)

model1 vs model2(mvc) : http://wiki.javajigi.net/pages/viewpage.action?pageId=73 �� ������ �����Ͽ���
model1 

![model1](images/model1.jpg)

���� : 
 - Model 1���� ����� ���� �������� ���� ���� ���ǰ� �ִ� ���� ���
 - ������ ���� �����ϱ� ������ �ܼ���.(ex : JSP / Servlet, PHP, ASP ��)
 - ���� �ӵ��� ������.
 - �������� ��ų�� ���Ƶ� ���� ���� ������ ����

���� :
 - ���������� ���������̼� ���� / ����Ͻ� ������ ��� �����ϹǷ� �������� �ʹ� ������ ����.
 - ���������̼� ���� / ����Ͻ� ������ ȥ��Ǿ� �ֱ� ������ �����ڿ� �����̳��� �и��� �۾��� ���������.
 - �������� �ڵ尡 ������ ������ ���� �������� �ϱ� ���������.

model2

![model1](images/mvc.jpg)

���� : 
 - Model 1 ���� ����� �������� �����Ͽ���.
 - ���������̼� ���� / ����Ͻ� ������ �и��ϹǷ� ��ɺ��� ���ȭ��
 - �����ڿ� �����̳ʰ��� �۾��� �����ϴ�.
 - �ڵ尡 �ܼ��� ������ ���� ���������� �����ϴ�.

���� : 
 - ����Ʈ���� ���� partten ������ �����Ͽ��� ��(���� ����� : �𸣴� ������Դ� model1���� ������ ���� �� ����)
 - ���� �ӵ��� model1���ٴ� ������.(�׷��� �ͼ������� model1���� ������.)


MVC ���� �� �帧�� : https://opentutorials.org/course/697/3828 �� ������ �����Ͽ���

 - ����
1. ����ڰ� ������Ʈ�� �����Ѵ�. (Uses)
2. Controller�� ����ڰ� ��û�� ���������� ���� �ϱ� ���ؼ� ���� ȣ���Ѵ�. (Manipulates)
3. ���� �����ͺ��̽��� ���ϰ� ���� ������ �ҽ��� ������ �Ŀ� �� ����� �����Ѵ�.
4. Controller�� Model�� ������ ����� View�� �ݿ��Ѵ�. (Updates)
5. �����Ͱ� �ݿ��� VIew�� ����ڿ��� ��������. (Sees)

 - ����
Controller :
����ڰ� ���� �� URL�� ���� ������� ��û������ �ľ��� �Ŀ� �� ��û�� �´� �����͸� Model�� �Ƿ��ϰ�, �����͸� View�� �ݿ��ؼ� ����ڿ��� �˷��ش�. 

Model :
�Ϲ������� CI(CodeIgniter)�� ���� �����ͺ��̽� ���̺� �����ȴ�. �̸��׸� Topic�̶�� ���̺��� topic_model�̶�� Model�� �����. �׷��� �� ���谡 ���������� �ʱ� ������ ��Ģ�� �ϰ��� �ְ� �����ϴ� ���� �ʿ��ϴ�.

View :
View�� Ŭ���̾�Ʈ �� ����� html/css/javascript���� ��Ƶ� �����̳��̴�. 

�ҽ��ڵ带 ���� mvc ��Ģ
(angular js ���� ���� - http://soomong.net/blog/2014/01/20/translation-ultimate-guide-to-learning-angularjs-in-one-day/ �� ����)

url : /angular/test1.do
controller : 
<script>
	//angular js ��� ����
	var myApp = angular.module('myApp', []);
	
	//controller ����
    	myApp.controller('MathCtrl', ['$scope', 'Math', function ($scope, Math) {
	    var a = 12;
	    var b = 24;

	    // ����� 288
		$scope.result = Math.multiply(a, b);
	}]);
	...
</script>
model : 
<script>
	...
	myApp.service('Math', function () {
	  this.multiply = function (x, y) {
	    return x * y;
	  };
	});
	...
</script>
view : 
<html>
<div ng-controller="MathCtrl">
	{{ result }}
</div>
</html>

�ҽ� ��ü 
<!DOCTYPE html>
<html>
<head>
<title>test</title>
<script type="text/javascript" src="/sti/js/jquery-1.11.3.js"></script>
<script type="text/javascript" src="/sti/js/jquery-migrate-1.2.1.js"></script>
<script type="text/javascript" src="/sti/js/angular.js"></script>
<script>
	//angular js ��� ����
	var myApp = angular.module('myApp', []);
	
	// Math
	myApp.service('Math', function () {
	  this.multiply = function (x, y) {
	    return x * y;
	  };
	});
	
	/*$scope - application ���� ��Ÿ���� angular js�� �⺻ ��ü*/
	myApp.controller('MathCtrl', ['$scope', 'Math', function ($scope, Math) {
	    var a = 12;
	    var b = 24;

	    // ����� 288
	    $scope.result = Math.multiply(a, b);
	}]);
</script>
</head>
<body>
    <div ng-controller="MathCtrl">
        {{ result }}
    </div>
</body>
</html>