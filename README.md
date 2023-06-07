# java-hw1
Реализуйте метод, принимающий в качестве аргументов два целочисленных массива, и возвращающий новый массив, каждый элемент которого равен частному элементов двух входящих массивов в той же ячейке. Если длины массивов не равны, необходимо как-то оповестить пользователя. Важно: При выполнении метода единственное исключение, которое пользователь может увидеть - RuntimeException, т.е. ваше.


		try 
			int [] arr1 = new GenerateArray().generateArray();
			int [] arr2 = new GenerateArray().generateArray();
			int [] result = new ProcessArray().arraysDifference(arr1, arr2);
			for (int a1 : arr1) System.out.printf("%d\t", a1);
		  for (int a2 : arr2) System.out.printf("%d\t", a2);
			System.out.println();
			System.out.println("Разница элементов двух массивов равна:");
			for (int i : result) System.out.printf("%d\t", i);
	    System.out.println(e.getMessage());
			System.out.printf(
					end
