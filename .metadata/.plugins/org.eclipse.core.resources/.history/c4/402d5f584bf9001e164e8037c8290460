package com.shopme.admin.user.controller;

import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.stereotype.Controller;
import org.springframework.web.bind.annotation.GetMapping;

import com.shopme.admin.user.service.UserService;

@Controller
public class UserController {

	@Autowired
	private UserService service;
	
	@GetMapping("/users")
	public String listAll() {
		return "users";
	}
	
}
