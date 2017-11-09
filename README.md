# Codeigniter-Login-and-Registration

Pulled code from the [following tutorial](http://www.kodingmadesimple.com/2016/06/codeigniter-login-and-registration-tutorial-source-code.html) to help give back to others looking to kickstart their development needs. 

Happy to help merge any improvements!


Run the follow the SQL commands within the application database to create the necessary user table.
```
CREATE TABLE IF NOT EXISTS `user` (
  `id` int(12) NOT NULL AUTO_INCREMENT,
  `fname` varchar(30) NOT NULL,
  `lname` varchar(30) NOT NULL,
  `email` varchar(60) NOT NULL,
  `password` varchar(40) NOT NULL,
  PRIMARY KEY (`id`),
  UNIQUE KEY `email` (`email`)
) ENGINE=MyISAM  DEFAULT CHARSET=latin1 AUTO_INCREMENT=1 ;
```
