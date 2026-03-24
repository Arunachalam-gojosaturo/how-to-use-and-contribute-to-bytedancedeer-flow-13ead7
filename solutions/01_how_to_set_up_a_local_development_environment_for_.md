# How to set up a local development environment for deer-flow

_Configure your local machine to run and test deer-flow_

## Steps

1. Clone the deer-flow repository using the command `git clone https://github.com/bytedance/deer-flow.git`
2. Install the required Python dependencies using `pip install -r requirements.txt`
3. Create a new virtual environment using `python -m venv deer-flow-env` and activate it with `source deer-flow-env/bin/activate`
4. Install the deer-flow package in editable mode using `pip install -e .`
5. Run the deer-flow server using `deer-flow start`

## Pitfalls

- ⚠️ Forgetting to activate the virtual environment before installing dependencies