package main

import (
	"fmt"
)

func Simulate(count_of_chacacters int) {
	if count_of_chacacters == 0 {
		fmt.Println("У вас нет ни одного персонажа.\nДля начала создайте персонажа, чтобы в будущем улучшить его. " +
			"Для создания введите запрос create.\nДля выхода из симулятора введите команду exit.")
		var our_request string
		fmt.Scanf("%s", &our_request)
		switch result := our_request; result {
		case "create":
			fmt.Println("Ваш персонаж создан")
			count_of_chacacters++
			Simulate(count_of_chacacters)
		case "exit":
			fmt.Println("Выход из программы...")
			break
		}
	}
}

func main() {
	fmt.Println("Здравствуйте дорогой пользователь!")
	count_of_chacacters := 0
	Simulate(count_of_chacacters)
}
