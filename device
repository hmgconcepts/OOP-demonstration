# Parent class
class Device:
    def __init__(self, brand, model):
        self.brand = brand
        self.model = model

    def info(self):
        return f"{self.brand} {self.model}"

# Child class
class Smartphone(Device):
    def __init__(self, brand, model, os, storage):
        super().__init__(brand, model)
        self.os = os
        self.storage = storage

    def make_call(self, number):
        return f"Calling {number} from {self.model}..."

    def install_app(self, app_name):
        return f"Installing {app_name} on {self.model}..."

# Example usage
phone = Smartphone("Samsung", "Galaxy S21", "Android", "128GB")
print(phone.info())
print(phone.make_call("08012345678"))
print(phone.install_app("WhatsApp"))
