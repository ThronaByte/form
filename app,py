from flask import Flask,render_template

app = Flask(__name__)

COURSE=[
    {
        'id':1,
        'name': 'Software Engineer',
        'Instructor': 'Senphil',
        'cost': '$200'
    },
    {
        'id':2,
        'name': 'Cyber Security',
        'Instructor': 'Ahmed',
        'cost': '$300'
    },
    {
        'id':3,
        'name': 'AWS Computing',
        'Instructor': 'Wade',
        'cost': '$300'
    }
]

@app.route('/')
def home():
    return render_template('home.html',
                           cour=COURSE)

if __name__ == '__main__':
    app.run(host='0.0.0.0', debug=True)