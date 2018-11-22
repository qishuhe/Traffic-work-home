from selenium import webdriver 

odkud = 'Dolní Břežany,Obecní úřad'
kam = 'Sídliště Písnice'

driver = webdriver.Chrome()
driver.get('http://pid.idos.cz/spojeni/')

odkud_box = driver.find_element_by_xpath("//input[@accesskey='O']")
odkud_box.send_keys(odkud)

kam_box = driver.find_element_by_xpath("//input[@accesskey='K']")
kam_box.send_keys(kam)

confirm_botton = driver.find_element_by_xpath("//input[@title='Vyhledat spojení']")
confirm_botton.click()

driver.execute_script("window.open('https://www.google.com/maps/@49.9813466,14.4603938,14z/data=!5m1!1e1');")
