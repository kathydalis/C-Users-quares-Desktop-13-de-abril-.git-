import unittest 
import chromedriver_binary
from selenium import webdriver
from selenium.webdriver.common.action_chains import ActionChains
from selenium.webdriver.common.keys import Keys
import time


class Test_navegador(unittest.TestCase):
    def setUp(self):
        self.driver = webdriver.Chrome(executable_path=r"C:\webdriver\chromedriver.exe")

    def test_inicio(self): 
        driver = self.driver
        driver.get("http://www.google.com")\
     


        self.driver.close()



if __name__ == '_main_':
    unittest.main()
