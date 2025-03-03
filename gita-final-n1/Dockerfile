# გამოვიყენე lightweight Python image
FROM python:3.10-alpine

# სამუშაო დირექტორიის შექმნა
WORKDIR /app

# ყველა საჭირო ფაილის ერთიანად კოპირება
COPY . /app/

# Flask-ის ინსტალაცია ფაილიდან
RUN pip install --no-cache-dir -r requirements.txt

# კონტეინერის პორტის გახსნა
EXPOSE 8000

# Flask სერვერის გაშვების ბრძანება
CMD ["python", "server.py"]
