# vue-localStorage
  a config file to manage localStorage of all data

# how to use
	1.include file to the main.js

	2.config file with the follow code:
		import Dao from './vue-localStorage.js'
		var dao = new Dao.Dao('myMoudleDao');
		Vue.prototype.dao=dao;
	
	3.now you can use in the whole system:
		set a value:
			this.dao.set('valueName','value');

		get a value:
			this.dao.get('valueName');
			
		remove a value:
			this.dao.remove('valueName');
