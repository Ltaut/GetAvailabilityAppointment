# GetAvailabalityAppointment

Send email for notify when practicien have disponibility.
You need the url from practicien page on doctolib or Maiia,
also need a motif if you don't know you can let it empty 
and he send list of consultation reason if no match identify 
with argument


## Requirements

- Python 3.10+
- pip or Poetry

## Installation

```bash
# Clone the repository
git clone https://github.com/luday94/GetAvailabilityAppointment.git
cd GetAvailabilityAppointment

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt
```

## Usage

```python
from your_package import main

result = main.run()
print(result)
```

## Configuration

| Variable | Description | Default |
|----------|-------------|---------|
| `url` | url from page of pratcicien  | Necesairy |
| `consultation_reason` | Reason for scheduling the appointment. | `False` |

## Testing

```bash
pytest
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Run tests with `pytest`
4. Submit a pull request

## Licence

GNU